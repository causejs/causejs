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
This will include JavaScript expressions, scoped variables, the ability to create commands on demand in the Cause config itself, variable binding and event triggering on variable/attribute change, the equivalent of setInterval for repeat events, custom element attribute binding, babel versions of the core, international character set support, shadow DOM, components within components, and a couple of other things. We've fixed a few bugs too.<br>
We're about 85% complete as of 19 Feb. Just wrapping up event handling from inside shadow DOM components, and that should be it for the new features. Then comes the task of updating the docs, getting sufficient examples that covers everything new, ironing out any bugs by setting up crazier unit tests offline (hopefully there shouldn't be many if any by this point), and setting up basic support for the extensions. We may release without the extensions being at full potential with the new features, but they will at least be functional...<br>
It is such a massive evolution and a big step for the language that we're moving up to version 2.0 with this one. It is still backward-compatible, except one of the commands has been renamed which shouldn't create a headache for anyone.<br>
It's suitably called the "Terrigen" release.<br>

Stay tuned!
