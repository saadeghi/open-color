# Open color

Open color is an [open-source](https://en.wikipedia.org/wiki/Open-source_software) color scheme optimized for UI like font, background, border, etc.

## Goals

- All colors shall have adequate use
- Provide general color for UI design
- All colors will be beautiful in itself and harmonious
- At the same brightness level, the perceived brightness will be constant

**Note**

* The colors are subject to change in the future. Thus, using an Open color as a main identity color is not recommended.

## Available Colors

![available colors](https://yeun.github.io/open-color/asset/images/open-color.svg)

## Installation

```
$ npm install open-color
```
```
$ bower install open-color
```

## Currently Supported Formats

css, sass, less, styl, json, svg, tex, oco(Open Color Tools), rcpx(PowerPaint), sketchpalette(Sketch), inkscape, aco, clr

## Variable Convention

### Sass, SCSS

```scss
$oc-(color)-(number)
```

### Less

```less
@oc-(color)-(number)
```

### Stylus

```styl
oc-(color)-(number)
```
### CSS

```css
--oc-(color)-(number)
```

---

- `oc`:  Abbreviation for Open color
- `(color)`: Color name such as gray, red, lime, etc.
- `(number)`: 0 to 9. Brightness spectrum.

## How to Use

Import the file to your project and use the variables.

**Example for Sass, SCSS**

```scss
@import 'path/open-color';

.body {
  background-color: $oc-gray-0;
  color: $oc-gray-7;
}

a {
  color: $oc-teal-7;

  &:hover,
  &:focus,
  &:active {
    color: $oc-indigo-7;
  }
}
```

**Example for Less**

```less
@import 'path/open-color';

.body {
  background-color: @oc-gray-0;
  color: @oc-gray-7;
}

a {
  color: @oc-teal-7;

  &:hover,
  &:focus,
  &:active {
    color: @oc-indigo-7;
  }
}
```

**Example for Stylus**

```styl
@import 'path/open-color.styl'

.body
  background-color: oc-gray-0
  color: oc-gray-7

a
  color: oc-teal-7

  &:hover
  &:focus
  &:active
    color: oc-indigo-7
```

**Example for CSS**

```css
@import 'path/open-color.css';

.body {
  background-color: var(--oc-gray-0);
  color: var(--oc-gray-7);
}

a {
  color: var(--oc-teal-7);
}

a:hover,
a:focus,
a:active {
  color: var(--oc-indigo-7);
}
```

## Contribution

Check out the list below.

### Color Value

- `open-color.json`
   - Change and `$ npm run compile-templates`
- `docs/asset/download/open-color_*.*.*.aco`
- `docs/asset/download/open-color_*.*.*.clr`
- Adobe library (admin rights)

### Version Number

- `package.json`
- `docs/asset/download/open-color_*.*.*.aco`
- Adobe library (admin rights)

### Document

- `README.md`
- `docs/documents.html`

### Introduction

- `README.md`
