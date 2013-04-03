# Resetize.css

CSS [reset](http://meyerweb.com/eric/tools/css/reset/) meets [normalize](http://necolas.github.com/normalize.css/).

---

## Rese what ?

The thing is I like the principles of normalize, but I miss the bar of reset.

I usually style `<b>` and `<strong>` to render in bold, `<code>` and `<pre>` using monospaced font face, etc. They are common and don't change often.

But I use to manually set the proportions between body text size and headings, white space between elements, and other stuff like that, they use to be very particular to the project being worked on.

**Resetize** is that, an opinionated marriage between two schools.

## OK, but what did you change ?

The baseline for the project is the awesome normalize.css. Normalize aims to keep the browser default style while removing the differences between browser.

I merely extended it by also reseting headings and form controls styles (font-weight, size, etc) and also removing paddings and margins from every block element. That's about it.

## That's interesting, I have my own thoughts about it too.

Great! Let me know what you think, what are your findings and what makes it easy for you to develop your layouts. Go open an issue and propose some changes, I'd love to hear from you!
