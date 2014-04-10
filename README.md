# Resetize.css

> An opinionated CSS reset.

## Rese.. what ?

At first I wanted to merge [normalize.css](http://necolas.github.io/normalize.css/) with a CSS reset, that's why the name is _resetize_.

But then I moved on to use a CSS reset with a few normalizations.

## And what is it like ?

The baseline for the project is the CSS reset from [HTML5 Doctor](http://html5doctor.com/), with a couple of changes:

- Changed `line-height` to `1.4` (it's a nice baseline and also prevents a few text rendering bugs)
- Reset the `margin` of form elements
- Changed `hr` color to `inherit`
- Left text formatting tags styled (like `b`, `strong`, `em`, `del`, `acronym`, etc..)
- Added [box-sizing reset](http://www.paulirish.com/2012/box-sizing-border-box-ftw/)
- Fix body height (set `background: none` on `html`)

## I have few ideas of my own...

Great! Let me know what you think, what are your findings and what makes it easy for you to develop your layouts. Go open an issue and propose some changes, I'd love to hear from you!

# License

See [CC Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/deed.en_US)
