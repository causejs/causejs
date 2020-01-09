# Cause JS
The JavaScript framework that looks like CSS.

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

Introducing Cause JS!

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

An important note on the Chrome extension permissions:<br>
The extensions need permissions to read and write on any website. This may seem extreme and put some people off from downloading the extensions, understandably. The thing is, the extensions only fully initialise on sites with the development version of the Cause core loaded. You can't hack sites about without the dev version of Cause loaded. The extensions need to be able to send data back and forth from the extension to the web page and back again, and they can work on any potential website - we don't know what websites you want to use the extensions on - hence it needs full permissions. So don't be put off. Google has to do a manual review of the extensions before approving such comprehensive privileges, so they are perfectly safe to use. No data is sent anywhere outside of your browser - there are no tracking or statistical, or actually any ajax calls of any kind going on in the background. Both extensions will work offline. You can't build these sorts of extensions without having those privileges unfortunately, but please rest assured that these are bonafide extensions.

News:<br>
After getting some feedback from the community, we are in the middle of a major overhaul to the development process so we can release the code as fully open-source on the MIT license and switch to a donation model.
We have a new release coming - JavaScript expression variables. This will go live at the same time as the open-source-ness occurs.
Stay tuned!
