# \<draw-element\>

`<draw-element>` is a simple draw component based on William Malone's app:
http://www.williammalone.com/articles/create-html5-canvas-javascript-drawing-app/#demo-simple

## Polymer Component for painting

Polymer Component that offers a canvas area where the user is able to paint with the mouse or the finger
depending on the device used, desktop or smartphone.

It is possible to customize the Component.

 Custom property | Description | Default
-----------------|-------------|---------
width | canvas width in pixels | 490
height | canvas height in pixels | 220
line-width | pen point width in pixels | 11
line-join | pen point shape, possible values: "round", "bevel", "miter" | "round"
line-color | paint colour in hexadecimal format | #df4b26
background-color | background colour in hexadecimal format | #fff8eb
border-color | canvas border colour in hexadecimal format | #d6d6d6

```html
<draw-element width="490" height="220" line-width="11" line-join="round" line-color="#df4b26" background-color="#fff8eb" border-color="#d6d6d6"></draw-element>
```

## Styling

 Custom property | Description | Default
-----------------|-------------|---------
--draw-element | Mixing applied to entire component | {}