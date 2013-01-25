# Resetize.css

CSS [reset](http://meyerweb.com/eric/tools/css/reset/) meets [normalize](http://necolas.github.com/normalize.css/).

---

## Rese what ?

The thing is I like the principles of normalize, but I miss the bar of reset.

I agree with the standard that says `<b>` and `<strong>` usually are rendered in bold, `<code>` and `<pre>` use a monospaced font face, etc. They are common and don't change often.

But I like to manually set the proportions between body text size and headings, they usually are very particular to the project being worked on.

**Resetize** is a just that, an opinionated marriage between two excellent projects.

## Good, but what did you change ?

### The baseline

The baseline for the project is the excellent reset.css, by Eric Meyer.

### Font family, weight and style

I kept some common standards like bold for `<b>` and `<strong>`, italic for `<i>` and `<em>`, and monospaced font for `<pre>`, `<code>` and `<var>`.

### Vertical align

The default value for `vertical-align` was `baseline`. But I noticed that while writing the layout I usually read from top-left to bottom-right. That said, changing the `vertical-align` to `top` seemed more obvious.

## That's interesting, I have my own thoughts about it too.

Great! Let me know what you think, what are your findings and what makes it easy for you to develop your layouts. Go open an issue and propose some changes, I'd love to hear form you!

