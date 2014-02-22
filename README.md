# Resetize.css

> CSS [reset](http://html5doctor.com/html-5-reset-stylesheet/) meets [normalize](http://necolas.github.com/normalize.css/).

---

## Rese.. what ?

The thing is I like the principles of normalize, but I miss the bar of CSS reset.

I usually style `<b>` and `<strong>` to render in bold, `<code>` and `<pre>` using monospaced font face, etc. They are very common and don't change often.

But I use to manually set the proportions between body text size and headings, white space between elements, and other stuff like that, they're very particular to the project being worked on.

**Resetize** is that, an opinionated marriage between the two.

## OK, but what did you change ?

The baseline for the project is the CSS reset from [HTML5 Doctor](http://html5doctor.com/). Actually very little was changed;

- Reset the `margin` of form elements to `0`
- Changed `hr` color to `gray`
- Left the tags `b`, `strong`, `i` and `em` styled

## I have few ideas of my own...

Great! Let me know what you think, what are your findings and what makes it easy for you to develop your layouts. Go open an issue and propose some changes, I'd love to hear from you!

# License

See [CC Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/deed.en_US)
