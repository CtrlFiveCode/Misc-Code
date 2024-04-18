# The @Keyframe Rule

## Example 1

When CSS Styles are specified inside the `@keyframes` rule, the animation gradually chages from the current style to the new style

To get the animation to work, it must be bound to an element

In [Example 1](./Example%201.html), the animation is bound to the `<div>` element. It lasts for 4 seconds, and gradually changes the background-color of the `<div>` from `"red"` to `"yellow"`

## Example 2

The `animation-duration` property defines how long an animation takes to complete. If the `animation-duration` property is not specified, no animation will occur, because the default value is `0 seconds`.

In [Example 1](./Example%201.html) we have specified when the style will change by using keywords `"from"` and `"to"` which represent `0% (start)` and `100% (complete)`.

It is also possible to use present, allowing you to add as many style changes as you want.

In [Example 2](./Example%202.html), the `background-color` of the `<div>` element will change when the animation is `25% complete`, `50% complete`, and again when it's `100% complete`. 

## Example 3

In [Example 3](./Example%203.html), both the `background-color` and the `position` of the `<div>` element when the animation is `25% complete`, `50% complete`, and again when it's `100% complete`.