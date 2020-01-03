# Cause JS
Cause JS - the JavaScript framework that looks like CSS.

Imagine that CSS was extended to have more event-driven functionality than the :hover event.

Imagine you could do this to put a class on the body tag when a hamburger icon was clicked:

```
#hamburger:click {
    body {
        add-class: .menuShowing;
    }
}
```

It's very direct, right? How much easier would other things be to code? Theoretically, of course...

What if there was now a language that could do this, and had loads more useful commands like this?

How much easier would it be to write and debug code? A lot, I bet!

What if you didn't have to worry about state management so much, and rely more on the DOM state with CSS selectors. CSS does that all the time, right? You don't have to have external state management for the state of styles, right? Theoretically, of course...

If only someone would write a language like this...

(drum roll...........)

Introducing Cause JS!

Cause JS is the first, truly 100% declarative programming language for the browser.
It does *not* have the hierarchical complexities of CSS, as this is a programming language, and that would be weird.
It comes with Chrome DevTools extensions for real-time event editing and monitoring, a bit like CSS.
It has a faster startup time than the popular frameworks, and weighs in at 15KB with brotli compression. It is designed to work as a companion to native JavaScript to make things simpler. Oh - and you can build SPAs with it.

Full documentation website
https://causejs.org

It works on modern browsers of the last couple of years. It won't work on IE and older browsers, and it is probably not worth polyfilling as it relies on the speed of today's querySelectorAll for its power. But do let us know if you find anything weird, and we'll look into it.
