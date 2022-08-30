# transform

The transform property is a powerful tool to change the appearance of elements without affecting the natural document flow.

## Two-Dimensional Transforms

`rotate`, `scale`, `skew`, and `translate`

```css

.element {
  transform: rotate();
}

```

```css
.element {
  transform: scaleX();
  transform: scaleY();
  transform: scale();
}

```

```css
.element {
  transform: skewX();
  transform: skewY();
  transform: skew();
}
```

```css
.element {
  transform: translateX();
  transform: translateY();
  transform: translate();
}
```

## Three-Dimensional Transforms

### Perspective

```css
.element {
  transform: perspective();
}
```

### Rotate

```css
.element {
  transform: rotateX();
  transform: rotateY();
  transform: rotateZ();
  transform: rotate3d();
}
```

### Matrix

```css
.element {
  transform: matrix();
  transform: matrix3d();
}
```