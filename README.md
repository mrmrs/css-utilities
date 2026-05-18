# css-utilities

Functional CSS for utilities

## Filesize

| File | Size |
|------|------|
| `dist/utilities.css` | 231 bytes |
| `dist/utilities.min.css` | 181 bytes (145 Gzipped) |

## Install

```sh
npm install css-utilities
```

## Usage

### Import

```css
@import "css-utilities";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-utilities/dist/utilities.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-utilities/dist/utilities.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.aspect-ratio` | `height: 0;   padding-top: 56.25%;   position: relative;` |
| `.aspect-ratio--object` | `z-index: 100;   width: 100%;   height: 100%;   position: absolute;   inset: 0;` |
| `.overflow-container` | `overflow-y: scroll;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.aspect-ratio-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/utilities.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/utilities.css` — formatted
- `dist/utilities.min.css` — minified

## License

MIT
