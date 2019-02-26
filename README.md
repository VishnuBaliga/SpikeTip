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

**CDN version (provided by [cdnjs](https://github.com/cdnjs/cdnjs)):**
```html
<link rel="stylesheet" href="..link..">
```

**Manually:**
Simply download `spiketip.min.css` from this repo and add it to your HTML. e.g.

```html
<link rel="stylesheet" href="path/to/spiketip.min.css">
```

### Positioning
For positioning, use `data-spiketip-pos` attribute with one of the values: `top`, `bottom`, `left`, `right`, `top-left`, `top-right`, `bottom-left` or `bottom-right`:

```html
<button data-spiketip="Whats up!" data-spiketip-pos="top">Hover me!</button>
<button data-spiketip="Whats up!" data-spiketip-pos="left">Hover me!</button>
<button data-spiketip="Whats up!" data-spiketip-pos="right">Hover me!</button>
<button data-spiketip="Whats up!" data-spiketip-pos="bottom">Hover me!</button>

<button data-spiketip="Whats up!" data-spiketip-pos="top-left">Hover me!</button>
<button data-spiketip="Whats up!" data-spiketip-pos="top-right">Hover me!</button>
<button data-spiketip="Whats up!" data-spiketip-pos="down-left">Hover me!</button>
<button data-spiketip="Whats up!" data-spiketip-pos="down-right">Hover me!</button>
```

### Showing tooltips programatically
If you want to show tooltips even when user interaction isn't happening, you can simply use the `data-spiketip-visible` attribute:

```html
<button data-spiketip="Whats up!" data-spiketip-pos="up" id="tooltip-element">Hover me!</button>
<script>
  const btn = document.getElementById('tooltip-element')
  btn.setAttribute('data-spiketip-visible', '')
</script>
```

 

### Credits

Made by Vishnu Baliga ([@Vishnu_Baliga](https://twitter.com/Vishnu_Baliga))