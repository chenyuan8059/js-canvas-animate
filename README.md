canvas-animate
===================

Animate folder images in canvas

## Latest Release

The latest version of the module is v0.5.0 `BETA`.

## Demo

[Click on link](https://keygenqt.ru/canvas)

## Usage

Html:

```html
<div id="canvas-animate-1"></div>

```

Js:
```js
var canvasAnimate = new CanvasAnimate('#canvas-animate-1', {
    mode: 'cover', // cover, center
    start: 39,
    fps: 25,
    pad: 4,
    desktopPath: '/video/1-full',
    mobilePath: '/video/1-mob'
});

$('#canvas-animate-1').click(function () {
    if (canvasAnimate.isPause()) {
        canvasAnimate.start();
    } else {
        canvasAnimate.pause();
    }
});

```



## License

**yii2-datepicker** is released under the BSD 3-Clause License. See the bundled `LICENSE.md` for details.


