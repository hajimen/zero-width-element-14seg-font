# Zero-width Element 14-seg font

<img src="readme/hello.svg" height="60" alt="Hello to Zero-width 14-seg font." />

Some 14-segment characters can have several variants. For example, B can have two variants:

<img src="readme/B-variant.svg" alt="B variant" />

Zero-width Element 14-seg font is a tool to design, review, and discuss about 14-segment character variants.
It contains 16 glyphs, U+0020 space, and empty U+005F low line (_).
Of these, 15 glyphs correspond to each segment. See below:

<img src="readme/segment.svg" alt="segments and glyphs" />

U+002E is full stop, namely "period." 

The 15 glyphs have zero-width, so you can combine them in a character.
You should place U+005F low line after each character. It is empty but has width.
Use U+0020 space as a word separator. It has width too.

The remaining one glyph is U+007E tilde (~). It contains all 15 elements and has width.

So why is this a good tool to design, review, and discuss about 14-segment character variants?
Because you can copy-and-paste the glyphs as ASCII text. From the ASCII text, you can generate font data, of course.

You can type and copy-and-paste it online, of course: <a href="https://kaoriha.org/zero-width-element-14seg-font/">Online Tester</a>

## Variation

Italic only.

## History

The glyph of Zero-width Element 14-seg font comes from [DSEG14 Classic-Italic](https://github.com/keshikan/DSEG).
Modified a bit.

## License

SIL OPEN FONT LICENSE Version 1.1
