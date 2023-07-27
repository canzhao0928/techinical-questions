# techinical-questions

## [HTML]

## CSS

## [JavaScript](#Q1-Explain-equality-in-JavaScript)

### Q1 Explain equality in JavaScript

JavaScript has both strict and type–converting comparisons:

- **Strict comparison (e.g., ===)** checks for value equality without allowing coercion
- **Abstract comparison (e.g. ==)** checks for value equality with coercion allowed

```JS-equality
var a = "42";
var b = 42;

a == b;			// true
a === b;		// false
```

### Q2 iframe

The iframe HTML element represents a nested browsing context, embedding another HTML page into the current one.

```
<iframe id="inlineFrameExample"
    title="Inline Frame Example"
    width="300"
    height="200"
    src="https://www.openstreetmap.org/export/embed.html?bbox=-0.004017949104309083%2C51.47612752641776%2C0.00030577182769775396%2C51.478569861898606&layer=mapnik">
</iframe>
```

### 03 how to hightlight text

```
<mark>text<mark>
```

```
<span style="background-color: yellow">text</span>
```

### 04 CSS sprite

Image sprites are used in numerous web apps where multiple images are used. Rather than include each image as a separate image file, it is much more memory- and bandwidth-friendly to send them as a single image; using background position as a way to distinguish between individual images in the same image file, so the number of HTTP requests is reduced.
