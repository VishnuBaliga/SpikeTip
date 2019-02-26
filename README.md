# SpikeTip Tooltip

## Simple tooltips made of pure CSS
SpikeTip lets you add tooltips to elements without JavaScript and in just a few lines of CSS.

## Demo & Playground

You can play with SpikeTip here: ..link...

## Usage

### Installation

**Using npm:**
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

### Positioning
For positioning, use `spiketip-pos` attribute with one of the values: `top`, `bottom`, `left`, `right`, `top-left`, `top-right`, `bottom-left` or `bottom-right`:

```html
<button spiketip-title="Whats up!" spiketip-pos="top">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="left">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="right">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="bottom">Hover me!</button>

<button spiketip-title="Whats up!" spiketip-pos="top-left">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="top-right">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="down-left">Hover me!</button>
<button spiketip-title="Whats up!" spiketip-pos="down-right">Hover me!</button>
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

Made by Vishnu Baliga ([@Vishnu_Baliga](https://twitter.com/Vishnu_Baliga))