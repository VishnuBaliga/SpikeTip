# SpikeTip Tooltip

[![npm version](https://badge.fury.io/js/spiketip-tooltip.svg)](https://badge.fury.io/js/spiketip-tooltip)

## Sleek tooltips spun from CSS
Javascript? Nah. Create effortless tooltips that breathe CSS!
No Javascript. Just the good old CSS.

## Demo & Playground

You can check more exaples at the website: https://spiketip.netlify.app

You can play with SpikeTip here: https://jsfiddle.net/Baliga/v72fyh6z/

## Usage

### Installation

**Using npm: (prerequisites: css-loader, style-loader)**
```
npm install spiketip-tooltip
```
```js
import 'spiketip-tooltip/spiketip.min.css'
```

**Manually:**
Simply download `spiketip.min.css` from this repo and add it to your HTML. e.g.

```html
<link rel="stylesheet" href="path/to/spiketip.min.css">
```

Alternatively, you can use it via CDN (provided by jsdelivr):

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/spiketip-tooltip@1.1.1/spiketip.min.css">
```

### Positioning
For positioning, use `spiketip-pos` attribute with one of the values: `top`, `bottom`, `left`, `right`, `top-left`, `top-right`, `bottom-left` or `bottom-right`:

```html
<button spiketip-title="Whats up!" spiketip-pos="top">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="left">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="right">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="bottom">Hover me!</button>

<button spiketip-title="Whats up!" spiketip-pos="top-left">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="top-right">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="bottom-left">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="bottom-right">Hover me!</button>
```
### Color Options
For positioning, use `spiketip-color` attribute with one of the values: `success`, `error`, `warning`, `info`:

```html
<button spiketip-title="Whats up!" spiketip-pos="top" spiketip-color="success">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="left" spiketip-color="error">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="right" spiketip-color="warning">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="bottom" spiketip-color="info">Hover me!</button>

<button spiketip-title="Whats up!" spiketip-pos="top-left" spiketip-color="warning">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="top-right" spiketip-color="info">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="bottom-left" spiketip-color="success">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="bottom-right" spiketip-color="error">Hover me!</button>
```

### Size
For sizing, use `spiketip-length` attribute with one of the values: `sm`, `md`, `lg`, `xl`, `auto`:

```html
<button spiketip-title="Whats up!" spiketip-pos="top" spiketip-length="sm">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="left" spiketip-length="md">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="right" spiketip-length="lg">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="bottom" spiketip-length="xl">Hover me!</button> 
<button spiketip-title="Whats up!" spiketip-pos="bottom" spiketip-length="auto">Hover me!</button> 
```

### Showing tooltips programatically
If you want to show tooltips even when user interaction isn't happening, you can simply use the `spiketip-visible` attribute:

```html
<button spiketip="Whats up!" spiketip-pos="up" id="tooltip-element">Hover me!</button>
<script>
  const btn = document.getElementById('tooltip-element')
  btn.setAttribute('spiketip-visible', '')
</script>
```

 

### Credits

Developed with ❤ by [Vishnu_Baliga](https://vishnubaliga.com/)
