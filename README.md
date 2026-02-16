# css-flex-align-content

Functional CSS for flex-align-content

## Filesize

| File | Size |
|------|------|
| `dist/flex-align-content.css` | 1817 bytes |
| `dist/flex-align-content.min.css` | 1425 bytes (242 Gzipped) |

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
| `.align-content-start` | `align-content: flex-start;` |
| `.align-content-end` | `align-content: flex-end;` |
| `.align-content-center` | `align-content: center;` |
| `.align-content-between` | `align-content: space-between;` |
| `.align-content-around` | `align-content: space-around;` |
| `.align-content-stretch` | `align-content: stretch;` |
| `.align-content-inherit` | `align-content: inherit;` |
| `.align-content-start-s` | `align-content: flex-start;` |
| `.align-content-end-s` | `align-content: flex-end;` |
| `.align-content-center-s` | `align-content: center;` |
| `.align-content-between-s` | `align-content: space-between;` |
| `.align-content-around-s` | `align-content: space-around;` |
| `.align-content-stretch-s` | `align-content: stretch;` |
| `.align-content-inherit-s` | `align-content: inherit;` |
| `.align-content-start-m` | `align-content: flex-start;` |
| `.align-content-end-m` | `align-content: flex-end;` |
| `.align-content-center-m` | `align-content: center;` |
| `.align-content-between-m` | `align-content: space-between;` |
| `.align-content-around-m` | `align-content: space-around;` |
| `.align-content-stretch-m` | `align-content: stretch;` |
| `.align-content-inherit-m` | `align-content: inherit;` |
| `.align-content-start-l` | `align-content: flex-start;` |
| `.align-content-end-l` | `align-content: flex-end;` |
| `.align-content-center-l` | `align-content: center;` |
| `.align-content-between-l` | `align-content: space-between;` |
| `.align-content-around-l` | `align-content: space-around;` |
| `.align-content-stretch-l` | `align-content: stretch;` |
| `.align-content-inherit-l` | `align-content: inherit;` |

### Responsive

Responsive variants are available for each class with the following suffixes:

| Suffix | Media Query              |
|--------|--------------------------|
| `-s`   | `min-width: 32em`        |
| `-m`   | `min-width: 48em`        |
| `-l`   | `min-width: 96em`        |

Example: `.align-content-start-m` applies the property at the medium breakpoint and above.

## Building

```sh
npm run build
```

Processes `src/flex-align-content.css` with [Lightning CSS](https://lightningcss.dev) and outputs to `dist/`.

- `dist/flex-align-content.css` — formatted
- `dist/flex-align-content.min.css` — minified

## License

MIT
