# Cause JS
The JavaScript framework for regular websites.

Imagine that CSS was extended to have more event-driven functionality than the :hover event.

Imagine you could do the following to put a class on the body tag when a hamburger icon was clicked:

```
#hamburger:click {
    body {
        add-class: .menuShowing;
    }
}
```

It's very direct, right? How much easier would other things be to code? Theoretically, of course...

How much easier would it be to write and debug code? A lot, I bet!

What if you didn't have to worry about state management so much, and rely more on the DOM state with CSS selectors. CSS does that all the time, right? It would be great to have a framework that just worked with the DOM, and didn't get too complicated, but be powerful enough to do what you needed it to do. And have an easy learning curve.

What if there was now a language that could do this, and had loads of useful commands you could apply like CSS?

(drum roll...........)

Introducing Cause JS!

Cause JS is the first, truly 100% declarative programming language for the browser.<br>
It does *not* have the hierarchical complexities of CSS. It has an easy learning curve, as it looks like CSS already.<br>
It comes with Chrome DevTools extensions for real-time event editing and monitoring, a bit like CSS.<br>
It has a faster startup time than the popular frameworks, and weighs in at 15KB with brotli compression. It is designed to work as a companion to native JavaScript to make things simpler. Oh - and you can build SPAs with it.

Full documentation website
https://causejs.org

It works on modern browsers of the last couple of years. It won't work on IE and older browsers, and it is probably not worth polyfilling as it relies on the speed of today's querySelectorAll for its power. But do let us know if you find anything weird, and we'll look into it.

Coming up soon in the next release...<br>
A new direct JavaScript expressions variable type to be used in action values, components, conditionals and target selectors! You have no idea what that means - that's ok - basically, we've started to attack UI component stuff. We are going to make a clock, purely within the event flow. And it's going to be really easy. Plus you'll be able to test JavaScript expressions from within the Elements extension in real-time...<br>
Stay tuned!<br>
Version 1.1.0 release date estimate: 6th January 2020.
