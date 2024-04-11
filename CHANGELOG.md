# Changelog

## Unreleased
* Add `backdrop-filter` support
* Fix nested `var` values
* Add support for logical properties:
  * `block-size`, `inline-size`, `max-block-size`, `max-inline-size`, `min-block-size`, `min-inline-size`
  * `margin-block`, `margin-block-end`, `margin-block-start`, `margin-inline`, `margin-inline-end`, `margin-inline-start`
  * `padding-block`, `padding-block-end`, `padding-block-start`, `padding-inline`, `padding-inline-end`, `padding-inline-start`
  * `border-block`, `border-block-color`, `border-block-end`, `border-block-end-color`, `border-block-end-style`, `border-block-end-width`, `border-block-start`, `border-block-start-color`, `border-block-start-style`, `border-block-start-width`, `border-block-style`, `border-block-width`, `border-inline`, `border-inline-color`, `border-inline-end`, `border-inline-end-color`, `border-inline-end-style`, `border-inline-end-width`, `border-inline-start`, `border-inline-start-color`, `border-inline-start-style`, `border-inline-start-width`, `border-inline-style`, `border-inline-width`, `border-style`, `border-width`
  * `border-start-start-radius`, `border-start-end-radius`, `border-end-start-radius`, `border-end-end-radius`
  * `inset`, `inset-block`, `inset-block-end`, `inset-block-start`, `inset-inline`, `inset-inline-end`, `inset-inline-start`
  * `contain-intrinsic-block-size`, `contain-intrinsic-inline-size`
  * `overflow-block`, `overflow-inline`, `overscroll-behavior-block`, `overscroll-behavior-inline`, `overscroll-behavior-x`, `overscroll-behavior-y`, `overscroll-behavior`
  * `inline-start` and `inline-end` values for `clear`, `float`, and `caption-side`
  * `fit-content()` function

## 0.6.1 - Fast Follow
* Fix regex compatibility error for animation names in Sublime Text 2
* Update the Changelog (oops)

## 0.6.0 - Hello Again
* Remove Atom support
* Add hex color alpha channel support
* Add `or` to mixin guards
* Add `if` function and logical comparisons
* Add `boolean` function
* Add `range` function

## 0.5.0 - Nesting
* Fix `var` in transform functions

## 0.4.3 - The Extra B
* Fix typos
* Fix infinite loop in media queries (thanks @samvtran)
* Fix nested selectors that begin with a combinator
* Rearrange property names to prevent premature matches

## 0.4.2 - Feedback Loop
* Simplify custom-ident patterns
* Add completions for Sublime Text
* Add deep, slotted, host, and host-context
* Fix animation-name and others (thanks @zvuc)

## 0.4.1 - Supports Report
* Fix `@supports` highlighting

## 0.4.0 - Selector Detector
* Improve meta scopes for selectors
* Fix variables and nesting in calc

## 0.3.2 - Choose Your Parents
* Improve interpolation for classes, ids, and parent selectors
* Fix `default()` scope

## 0.3.1 - I'm still learning here
* Published to VS Code Marketplace

## 0.3.0 - Visualize it
* Add preliminary support for VS Code

## 0.2.1 - Imported Goods
* Fix `@import` statements with media queries

## 0.1.1 - This is Happening
* Fix semicolons for mixins at top of scope
* Fix ranges for Sublime Text 2
* Update README

## 0.1.0 - First Release
* Added support for Atom