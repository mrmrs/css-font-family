# css-font-family

Functional CSS for font-family

## Filesize

| File | Size |
|------|------|
| `dist/font-family.css` | 1249 bytes |
| `dist/font-family.min.css` | 945 bytes (217 Gzipped) |

## Install

```sh
npm install css-font-family
```

## Usage

### Import

```css
@import "css-font-family";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-font-family/dist/font-family.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-font-family/dist/font-family.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.serif` | `font-family: georgia, serif;` |
| `.sans-serif` | `font-family: avenir, avenir next, helvetica, arial, sans-serif;` |
| `.font-fantasy` | `font-family: fantasy;` |
| `.font-cursive` | `font-family: cursive;` |
| `.font-mono` | `font-family: monospace;` |
| `.serif-s` | `font-family: georgia, serif;` |
| `.sans-serif-s` | `font-family: avenir, avenir next, helvetica, arial, sans-serif;` |
| `.font-fantasy-s` | `font-family: fantasy;` |
| `.font-cursive-s` | `font-family: cursive;` |
| `.font-mono-s` | `font-family: monospace;` |
| `.serif-m` | `font-family: georgia, serif;` |
| `.sans-serif-m` | `font-family: avenir, avenir next, helvetica, arial, sans-serif;` |
| `.font-fantasy-m` | `font-family: fantasy;` |
| `.font-cursive-m` | `font-family: cursive;` |
| `.font-mono-m` | `font-family: monospace;` |
| `.serif-l` | `font-family: georgia, serif;` |
| `.sans-serif-l` | `font-family: avenir, avenir next, helvetica, arial, sans-serif;` |
| `.font-fantasy-l` | `font-family: fantasy;` |
| `.font-cursive-l` | `font-family: cursive;` |
| `.font-mono-l` | `font-family: monospace;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.serif-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/font-family.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/font-family.css` — formatted
- `dist/font-family.min.css` — minified

## License

MIT
