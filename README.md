# css-flex-align-content

Functional CSS for flex-align-content

## Filesize

| File | Size |
|------|------|
| `dist/flex-align-content.css` | 1389 bytes |
| `dist/flex-align-content.min.css` | 997 bytes (231 Gzipped) |

## Install

```sh
npm install css-flex-align-content
```

## Usage

### Import

```css
@import "css-flex-align-content";
```

### CDN

```html
<link rel="stylesheet" href="https://unpkg.com/css-flex-align-content/dist/flex-align-content.min.css">
```

### Direct

```html
<link rel="stylesheet" href="path/to/css-flex-align-content/dist/flex-align-content.min.css">
```

## Classes

| Class   | Value                    |
|---------|--------------------------|
| `.ac-fs` | `align-content: flex-start;` |
| `.ac-fe` | `align-content: flex-end;` |
| `.ac-c` | `align-content: center;` |
| `.ac-sb` | `align-content: space-between;` |
| `.ac-sa` | `align-content: space-around;` |
| `.ac-s` | `align-content: stretch;` |
| `.ac-i` | `align-content: inherit;` |
| `.ac-fs-s` | `align-content: flex-start;` |
| `.ac-fe-s` | `align-content: flex-end;` |
| `.ac-c-s` | `align-content: center;` |
| `.ac-sb-s` | `align-content: space-between;` |
| `.ac-sa-s` | `align-content: space-around;` |
| `.ac-s-s` | `align-content: stretch;` |
| `.ac-i-s` | `align-content: inherit;` |
| `.ac-fs-m` | `align-content: flex-start;` |
| `.ac-fe-m` | `align-content: flex-end;` |
| `.ac-c-m` | `align-content: center;` |
| `.ac-sb-m` | `align-content: space-between;` |
| `.ac-sa-m` | `align-content: space-around;` |
| `.ac-s-m` | `align-content: stretch;` |
| `.ac-i-m` | `align-content: inherit;` |
| `.ac-fs-l` | `align-content: flex-start;` |
| `.ac-fe-l` | `align-content: flex-end;` |
| `.ac-c-l` | `align-content: center;` |
| `.ac-sb-l` | `align-content: space-between;` |
| `.ac-sa-l` | `align-content: space-around;` |
| `.ac-s-l` | `align-content: stretch;` |
| `.ac-i-l` | `align-content: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.ac-fs-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/flex-align-content.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/flex-align-content.css` — formatted
- `dist/flex-align-content.min.css` — minified

## License

MIT
