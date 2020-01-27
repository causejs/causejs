# Cause JS
## The JavaScript framework that looks like CSS.
### Modern web programming simplified

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

### Next release:<br>
This will include JavaScript expressions, proper variables with scoping per component or project, the ability to create commands in the Cause config, which is really cool, one-way variable data-binding, babel versions of the core, international character set support, and further support for native web components, ie. shadow DOM and a couple of other things. We've fixed a few bugs too.<br>
In fact, it's such a massive evolution that we're moving up to version 2.0. It shouldn't affect backward compatibility much, if at all. It's suitably called the "Terrigen" release.<br>
New ETA, looks like a couple of weeks. Maybe a couple more weeks due to the bombshell news we received this morning, as we're going to have to make radical changes to avoid this happening in the future. See below.

### Update at of 25th January 2020:<br>
Google, in their infinite wisdom, has taken down our extensions from the Chrome Webstore for no valid reason.<br>
We have a back-up plan in case this ever happened, so it should be fine. Bit annoying though.<br>
Stay tuned.
