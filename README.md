# overflow.css

CSS `overflow` classes

## classes

### `overflow`
- `.overflow-visible`
- `.overflow-hidden`
- `.overflow-scroll`
- `.overflow-auto`

### `overflow-x`
- `.ox-visible`
- `.ox-hidden`
- `.ox-scroll`
- `.ox-auto`

### `overflow-y`
- `.oy-visible`
- `.oy-hidden`
- `.oy-scroll`
- `.oy-auto`

## setup

```
npm install overflow.css
```

```css
@import 'node_modules/overflow.css/overflow';
```

## usage

### example using `overflow`

```html
<blockquote
  class="overflow-auto"
  cite="https://drafts.csswg.org/css-overflow-3/#overflow-properties">
  <p>These properties specify whether a box’s content (including any ink overflow) is clipped to
    its padding edge, and if so, whether it is a scroll container that allows the user to scroll
    clipped parts of its scrollable overflow region into view. The visual viewport of the scroll
    container (through which the scrollable overflow region can be viewed) coincides with its
    padding box, and is called the scrollport.
</blockquote>
```

### example using both `overflow-x` and `overflow-x`

```html
<blockquote
  class="oy-auto ox-hidden"
  cite="https://drafts.csswg.org/css-overflow-3/#overflow-properties">
  <p>The overflow-x property specifies the handling of overflow in the horizontal direction
    (i.e., overflow from the left and right sides of the box), and the overflow-y property
    specifies the handling of overflow in the vertical direction (i.e., overflow from the top
    and bottom sides of the box).
</blockquote>
```
