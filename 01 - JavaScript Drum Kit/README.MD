# Day1 - JavaScript Drum Kit
create a Drum Kit by using JavaScript

## Conception
* detect which key was pressed down(add event listener`keydown`)
* find audio and div elements `[data-key="keyCode"]`
* when key press down, play audio --`audio.play()`
* on the same time, add class -- `element.classList.add('className')`
* after `transform` finish, remove it -- `element.classList.remove('className')`

## What I learn
* using `<kbd></kbd>` tag
The HTML Keyboard Input element (`<kbd>`) represents a span of inline text denoting textual user input from a keyboard, voice input, or any other text entry device. 

* using data-*, customise value which connect `<audio>`
`<element data-* = "somevalue">`

* In CSS
in this case `font-size: 10px` -> `1rem` is 10px, so `1.2rem` is 12px
`transform: scale (1.1)` --The `transform` property applies a 2D or 3D transformation to an element. This property allows you to rotate, scale, move, skew, etc., elements.