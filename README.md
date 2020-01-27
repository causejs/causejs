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

### Next release:<br>
This will include JavaScript expressions, proper variables with scoping, the ability to create commands in the Cause config, one-way variable data-binding, babel versions of the core, international character set support, and further support for native web components, ie. shadow DOM commands and a couple of other things. We've fixed a few bugs too. The core is still about the same size as it was.<br>
But it's such a massive evolution that we're moving up to version 2.0.<br>
It's suitably called the "Terrigen" release.<br>
ETA looks like a couple of weeks. Maybe a couple more weeks due to the bombshell news we received on Saturday morning, as we're going to have to make radical changes to not be at the mercy of random weird actions by 3rd parties. See below.

### Update at of 25th January 2020:<br>
Google, in their infinite wisdom, has taken down our extensions from the Chrome Webstore for no valid reason. It looks like it was an automatic take-down. The extensions passed manual reviews to go live, and we thought all was ok. They lasted a month. We haven't been told why the extensions were taken down. There is nothing malicious in the code, as you will see when we fully release them open source later on in the year. As we haven't yet done any promotion for Cause (though we mentioned it once in a forum to get initial feedback and got a lot of good response and a few github stars), thankfully no one has yet downloaded the extensions (our testers use in-house uploads), so no one that is public is affected. We will not let this happen again though, so we are implementing a back-up solution that we had in reserve in case this ever happened. Then, when we do go into promotion overdrive, we can ensure a smooth ride.<br>
Stay tuned!
