# Cause JS
## The JavaScript framework that looks like CSS.

Imagine that CSS was extended to have more event-driven functionality than the :hover event.

Imagine you could do the following to put a class on the body tag when a hamburger icon was clicked:

```
#hamburger:click {
    body {
        add-class: .menuShowing;
    }
}
```

It's very direct, right? How much easier would other things be to code?

What if you could rely more easily on the DOM state with CSS selectors. CSS does that all the time, right? It would be great to have a framework that just worked with the DOM, and didn't get too complicated, but be powerful enough to do what you needed it to do. And have an easy learning curve.

What if there was now a language that could do this, and had loads of useful commands you could apply like CSS?

(drum roll...........)

### Introducing Cause JS!
#### Modern web programming simplified

Cause JS is the first, truly 100% declarative programming language for the browser.<br>
It does *not* have the hierarchical complexities of CSS. It has an easy learning curve, as it looks like CSS already.<br>
It comes with Chrome DevTools extensions for real-time event editing and monitoring, a bit like CSS.<br>
It has a faster startup time than the popular frameworks, and weighs in at 15KB with brotli compression.<br>
It is designed to work as a companion to native JavaScript to make things simpler.<br>
You can also build single-page applications with it.<br>
Old-schoolers can use it as a plug-in, just like jQuery. New-schoolers can run it as an npm module.

Full documentation website and installation instructions:
https://causejs.org

It works on modern browsers of the last couple of years. It won't work on IE and older browsers, and it is probably not worth polyfilling as it relies on the speed of today's querySelector for its power.

### News:<br>
After getting some feedback from the community, we have completed a major overhaul to the development process so we can release the code as fully open-source (ie. not minified - so you can fork it properly) on the MIT license and switch to a donation model. This will go live with the next release. Full source code for the browser extensions will be following soon after - they need a bit of refactoring and tidy-up before they go public...

### Next major release imminent-ish:<br>
This will include JavaScript expressions, the ability to create commands on demand in the Cause config itself, variable binding and event triggering on variable/attribute change, the equivalent of setInterval for repeat events, labelling of individual actions for isolated delay cancelling, custom element attribute binding, babel versions of the core, international character set support, shadow DOM, easy variable scoping to the document scope or private shadow DOM scopes, components within components, and a couple of other things, including a proper looping syntax. We've fixed a few bugs too.<br>
We're about 92% complete as of 7 March.<br>

Here's a sneak peak of the new shadow DOM interface - DOMs within DOMs (just a small part of the interface, to give you a taste). This puts four shadow DOMs inside each other in a custom <babushka-box></babushka-box> tag. You'll notice that it is a lot easier doing it this way than in native JavaScript. A lot less waffle:
```
babushka-box:draw {
    create-element: babushka-box;
    render: "{|Box-1}";
}

@component Box-1 shadow open {
    html {
        <div>I am in a shadow DOM tree.</div>
        <div>{|Box-2}</div>	/* render another shadow DOM tree here */
        <style>
            div {
                font-size: 20px;
            }
        </style>
    }
}

@component Box-2 shadow open {
    &:shadowOpen {
        div {
            render-after-end: "<div>{|Box-3}</div>";
        }
        document -> h1 {
            render-after-end: "<h2>AKA: That\'s quite a lot of shadow DOMs.</h2>";
        }
        host {
            render-before-end: "<p>You can do this as well.</p>";
        }
    }
    html {
        <div>I am in a shadow DOM tree inside a shadow DOM tree.</div>
        <style>
            div {
                font-size: 18px;
            }
        </style>
    }
}

@component Box-3 shadow open {
    html {
        <div>I am in a shadow DOM tree inside a shadow DOM tree inside a shadow DOM tree.</div>
        <div>{|Box-4}</div>
        <style>
            div {
                font-size: 16px;
            }
        </style>
    }
}

@component Box-4 shadow closed {
    html {
        <div>I am in a shadow DOM tree inside a tree inside a tree inside a tree.</div>
        <style>
            div {
                font-size: 14px;
            }
        </style>
    }
}
```

It is such a massive evolution and a big step for the language that we're moving up to version 2.0 with this one. It is still backward-compatible, except two commands have been renamed which shouldn't create a massive headache for anyone.<br>
It's suitably called the "Terrigen" release, as it has the potential to create a quake or two.<br>

Stay tuned!
