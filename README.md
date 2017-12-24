[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/owner/my-element)

# \<press-button\>

This is button element. But not react by click. It need press action.
It need press at 1 second(default). If release press before end. It mean is cancel.

## DEMO

<!--
```html
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="press-button.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<div style="padding: 100px 0 0">
<press-button type="button" raised>PRESS ME</press-button>
</div>
```

## Installation

```
$ bower install --save monkick/press-button
```

## Usage

At first. Import it at header.  

```html
    <link rel="import" href="../bower_components/press-button/press-button.html">
```

Next. Add the `press-button` custom tag in body.

```html
    <press-button type="button" raised>PRESS ME</press-button>
```

* `type` Choice action type button or submit
* `raised` Design of floating


## CSS

| key | description |
----|---- 
| --press-button | button style |
| --loading-circle | indicater style |
| --loading-background | indicater background style |
| --loading-text |indicater end text(svg) style |
| --circle-animation | indicater animation style |