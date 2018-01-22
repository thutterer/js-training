# JavaScript 101

This is a [remark](https://remarkjs.com/) slide-deck I created for a training I gave.

The idea was to start with the history from the early days till today.
And then to jump into the cold water and explain the syntax (quirks) while hacking.
So after the end of of the slide-deck, the exercise was to create a simple digital clock.

The steps through which I guided the trainees were as follows:

- start with a blank document and add and explain the basic HTML structure
- `document.write` and `console.log` something
- slice `(new Date).toTimeString` and write it in a page element
- move the code into a function and `window.setInterval` on it
- put the code into its own file with `<script src='clock.js'>`
- add some basic CSS styling, explain and move it into `clock.css`
- add buttons to turn the display of seconds on and off (to show event handlers)
- explain differences between `var`, `let` and `const` (scopes) and many other gotchas along the way

A clean version of the desired end result can be found in this [repo](https://github.com/thutterer/now).
