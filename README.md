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
You can also build SPAs with it.<br>
Old-schoolers can use it as a plug-in, just like jQuery. New-schoolers can run it as an npm module.

Full documentation website and installation instructions:
https://causejs.org

It works on modern browsers of the last couple of years. It won't work on IE and older browsers, and it is probably not worth polyfilling as it relies on the speed of today's querySelector for its power.

### News:<br>
After getting some feedback from the community, we have completed a major overhaul to the development process so we can release the code as fully open-source (ie. not minified - so you can fork it properly) on the MIT license and switch to a donation model. This will go live with the next release. Full source code for the browser extensions will be following soon after - they need a bit of refactoring and tidy-up before they go public...

### Next major release:<br>
This will include JavaScript expressions, proper variables with scoping, the ability to create commands in the Cause config, one-way data-binding, babel versions of the core, international character set support, shadow DOM, web components and a couple of other things. We've fixed a few bugs too.<br>
We're about 65% complete as of 12 Feb. Getting the end-user syntax right is the hardest part of Cause core work. The web components and shadow DOM Cause syntax has finally been nailed down successfully after several prototyping possibilities failed (which you would appreciate is quite a feat if you have ever tried to work with web components), and we are having fun implementing this now. Maybe fun is not quite the right word...<br>
It's such a massive evolution that we're moving up to version 2.0 with this one.<br>
It's suitably called the "Terrigen" release.<br>

Stay tuned!
