# Line

extends from Geometry.

## Constructor

```js
new Line({
    group,
    startPoint = { x: 0, y: 0 },
    endPoint,
    lineColor = "#fff",
    lineWidth = 2,
});
```

## Properties

See [Cubicon()](./reference/cubicon/cubicon.md) properties.

> #### .startPoint: Vector2

Tail of the line.

> #### .endPoint: Vector2

Head of the line.

> #### .lineColor: String

Color of the line.

> #### .lineWidth: Number

Width of the line.

## Getters

> #### .WstartPoint: Number

Tail of the line (in SVG-Cartesian coordinates system).

> #### .WendPoint: Number

Head of the line (in SVG-Cartesian coordinates system).

## Methods

No method is attached to this class.
