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
This will include JavaScript expressions, the ability to create commands on demand in the Cause config itself, variable binding and event triggering on variable/attribute change, the equivalent of setInterval for repeat events, labelling of individual actions for isolated delay cancelling, custom element attribute binding, babel versions of the core, international character set support, shadow DOM (incl. templates and slots), easy variable scoping to the document scope or private shadow DOM scopes, components within components, and a couple of other things, including a proper looping syntax (@each - similar to SASS syntax) and the ability to add straight-up CSS commands alongside the Cause commands. We've fixed a few bugs too, optimized some areas, and it appears to be even faster than it was. We're also changing the name of the project to something more appropriate.<br>

The extensions will automatically use the code that is established to work for different core versions, so in theory they will always be backward-compatible, even if there are drastic changes to the core. The source code for Elements and Panel extensions will be published at some point soon, to give people guidance on writing extensions for Cause, and a fall-back option from the Chrome webstore for those who can handle manually extension compiling. We might charge a small fee for being able to use the Chrome webstore for installing the extensions and keeping them auto-updating. We are planning on rolling-out free Firefox extensions too if the Firefox API can handle it.<br>

We're about 97% complete as of 28 March. Getting the docs website ready and doing a redesign, which takes frikkin ages being the perfectionists that we are. We want to make sure it's right and everything works. Be patient - it will be worth it! Sorry for any delay. We literally don't know if anyone else is actively using it, as we haven't wanted to promote this until we finished this release, so let us know if you are so we can say hi!

Here's a sneak peak of the new shadow DOM interface:

```
<custom-el></custom-el>
```
```
custom-el:draw {
    create-element: custom-el;
    render: "{|myShadow}";
}

@component myShadow shadow open {
    html {
        <div>I am in a shadow DOM tree. Inspect in DevTools.</div>
        <style>
            div {
                font-size: 20px;
            }
        </style>
    }
}
```

The whole release is such a massive evolution and a big step for the language that we're moving up to version 2.0 with this one. It is still sort-of backward-compatible-ish, except two commands have been renamed, and the component syntax has changed a little bit to allow for adding events within the component.<br>
We'll give instructions as to what to change. It won't be nightmare, I promise :)
It's suitably called the "Terrigen" release, as it has the potential to create a quake or two.<br>

Stay tuned!

