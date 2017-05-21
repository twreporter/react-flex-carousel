# react-flex-carousel
A simple responsive Carousel powered by React and CSS Flexbox

You can also try [nuka-carousel](https://github.com/kenwheeler/nuka-carousel) if needed more features.


## Feature

* Support swipe touch gesture
* CSS style customization

## Usage
```js
<Carousel className="slider" autoplayInteval={4500} indicator={true} switcher={true}>
	<div></div>
	<div></div>
	<div></div>
</Carousel>
```

### Props

* `className`:
	class name on Carousel for CSS styling
* `autoplayInteval`:
	set inteval number in ms to enable carousel autoplay
* `transitionDuration`:
	CSS transition-duration, default is `.8s`
* `transitionTimingFunction`:
	CSS transition-timing-function, default is `ease-in-out`
* `switcher`:
	toggle to show the prev/next buttons, default is `false`
* `indicator`:
	toggle to show the indicator dots, default is `false`

Then apply your style, take `slider.css` for reference.

## Demo

Install [nwb](https://github.com/insin/nwb), then `react run example.js` to see the demo.

## License

MIT
