{{ target: echarts-graphic }}

## graphic

Util methods about grphics.

### clipPointsByRect(Function)

Clip the given points by the given rectangular.

```js
(
    // The points to be clipped, like [[23, 44], [12, 15], ...].
    points: Array.<Array.<number>>,
    // The rectangular that is used to clip points.
    rect: {
        x: number,
        y: number,
        width: number,
        height: number
    }
) => Array.<Array.<number>> // The result Points.
```

### clipRectByRect(Function)

Clip the first input rectangular by the second input rectangular.

```js
(
    // The rectangular to be clipped.
    targetRect: {
        x: number,
        y: number,
        width: number,
        height: number
    },
    // The rectangular that is used to clip the first  rectangular.
    rect: {
        x: number,
        y: number,
        width: number,
        height: number
    }
) => { // The result rectangular.
    x: number,
    y: number,
    width: number,
    height: number
}
```


