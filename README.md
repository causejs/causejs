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

News:<br>
After getting some feedback from the community, we have completed a major overhaul to the development process so we can release the code as fully open-source (ie. not minified - so you can fork it properly) on the MIT license and switch to a donation model. This will go live with the next release.

Next release:<br>
This will include JavaScript expressions, variables, the ability to create commands in the Cause config, true data-binding, babel versions of the core, international character set support, and further support for native web components and a couple of other things. We've only got variables and data-binding left to do now, and that syntax has now been established and the coding will be finished and onto unit testing over the next couple of days. Coding is the easy bit. It's the designing of the syntax that most people, especially red-taped committees, have trouble with. CSS variables are flawed in that they look like "--blah", which means they can't be sustituted easily into anything, hence we get var(blah), which is messy, and it limits calculation ability and what's with the extra space placed after var(), so it can't be substituted predictably? Weird. It is so limiting for an actual language, and they didn't think it through. Even gods can get it wrong. So we're not following CSS variable format, which should just stick to styles, and we're doing something simpler for the actual language. Yes, that is correct, simpler. And with sensible scoping too. We have some docs changes to do also before going live, and sufficient examples. This release is a meaty one, but it is all needed at once, as they are interrelated and we wanted to get the syntax right. At the moment, everything is backwards compatible too (I think). It's looking more and more awesome, and we are very excited! New ETA, looks like a couple of weeks. Maybe a week later due to the bombshell news we received this morning. See below.

Update at of 25th January 2020:<br>
Google, in their infinite wisdom, has taken down our extensions from the Chrome Webstore. Why? Who knows. The extensions apparently went through manual reviews, which took ages, but passed those. A month after they were up, they are without warning mysteriously taken down. Either there is a valid reason why that they haven't told me, or something else is afoot. Either way, I'll give them a week to sort it out. If they haven't gotten their act together after that, we're going to switch to manual extension downloads. We are not backing down to any corporation and we don't need them. It is really easy to load extensions manually, and you can then tweak the source code if you want. It will actually mean we can release new updates faster, as we don't have to wait a week for Google to patronisingly deem our products worthy before we can release. We'll also try and sort out Firefox versions of the extensions too. Firefox has been catching up on the DevTools API recently, as it has been a bit lacking in functionality in the past, which has been why we've only done Chrome versions to date. We will reinstate our e-commerce module for the Panel and bypass Google altogether if necessary. There are plenty of other browsers. They do not own the internet, despite their attempts to do so. We have a long-standing record of being persistent AF. We are sufficiently irritated about this action by Google, as you can probably gather :) Please bear with us if we have to make this change. It will be worth it. Thank you!
