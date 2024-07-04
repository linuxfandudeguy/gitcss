
# GitCSS Documentation

## Introduction

GitCSS is a lightweight CSS framework designed for easy integration and customization in web projects. It provides a set of utility classes to style various elements quickly.

## Getting Started

To use GitCSS, include the following link in your HTML `<head>` section:

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/linuxfandudeguy/gitcss@firstver/git.css">
```

Replace `firstver` with the specific release tag or version you want to use.

## Utility Classes

### Font Classes

- `.font-primary`: Sets the primary font family.
- `.font-secondary`: Sets the secondary font family.
- `.font-weight-400`, `.font-weight-500`, `.font-weight-700`: Sets font weights.
- `.font-italic`, `.font-normal`: Sets italic or normal font style.

```html
<p class="font-primary font-weight-500">Primary Font, Weight 500</p>
<p class="font-secondary font-italic">Secondary Font, Italic</p>
```

### Color Classes

- Background Colors: `.bg-primary`, `.bg-secondary`, `.bg-accent`
- Text Colors: `.text-primary`, `.text-secondary`, `.text-accent`
- Border Colors: `.border-primary`, `.border-secondary`, `.border-accent`

```html
<div class="bg-primary text-white">Primary Background, White Text</div>
<div class="bg-secondary text-black">Secondary Background, Black Text</div>
<div class="bg-accent border-accent">Accent Background, Accent Border</div>
```

### Gradient Classes

- `.bg-gradient-primary`, `.bg-gradient-secondary`: Applies gradients to backgrounds.
- `.text-gradient-primary`: Applies gradient to text (using `-webkit-text-fill-color`).

```html
<div class="bg-gradient-primary">Primary Gradient Background</div>
<div class="text-gradient-primary">Primary Gradient Text</div>
```

### Button Classes

- `.btn`: Basic button styling.
- `.btn-primary`, `.btn-secondary`, `.btn-accent`: Styled buttons with different colors.
- `.btn-gradient-primary`, `.btn-gradient-secondary`: Gradient buttons.
- `.btn-font-primary`, `.btn-font-secondary`: Sets font family for buttons.

```html
<button class="btn btn-primary">Primary Button</button>
<button class="btn btn-secondary btn-gradient-secondary">Secondary Gradient Button</button>
```

### Container Class

- `.container`: Styles containers with max-width, padding, border-radius, and box-shadow.

```html
<div class="container">
  <h2>Container Example</h2>
  <p>This is a styled container.</p>
</div>
```

## Conclusion

GitCSS offers a variety of utility classes to enhance your web designs with minimal effort. 
