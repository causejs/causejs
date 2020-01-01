# Cause JS
Cause JS - the JavaScript framework that looks like CSS.

Imagine that CSS was extended to have more event-driven functionality than the :hover event.

Imagine you could do this to put a class on the body tag when a hamburger icon was clicked:

```
#hamburger:click {
    body {
        add-class: showMenu;
    }
}
```

It's very direct, right? How much easier would other things be to code? Theoretically, of course...

What if there was a now language that could do this, and had loads more useful commands like this?

How much easier would it be to write and debug code? A lot, I bet!

Introducing Cause JS!

Cause JS is the first, truly 100% declarative programming language for the browser.
It does *not* have the hierarchical complexities of CSS, as this is a programming language, and that would be weird.
It comes with Chrome DevTools extensions for real-time event editing and monitoring, a bit like CSS.
I has a faster startup time than the popular frameworks, and weighs in at 15KB with brotli compression.

Full documentation website
https://causejs.org

It works on modern browsers of the last couple of years. It won't work on IE and older browsers, and it is probably not worth polyfilling as it relies on the speed of today's querySelectorAll for its power. But do let us know if you find anything weird, and we'll look into it.


Boring copyright note:
----------------------

We're going to keep the development in-house for a while, but you can fork it and mod the core to your hearts content for use on websites, so to that extent it is open-source, and we'll let you republish the core with your own version of the language, but only if you include the word "causejs" in the title. We didn't spend thousands of hours on this just to be ripped off :)

If you build commands that you want to be part of the official core, let us know through the support form on our website (https://causejs.org/support.html), and we will set up an alternative language library, or include your commands in the core and give you a credit, something like that. We haven't worked it out yet.

License notes:
https://causejs.org/terms-and-conditions.html
