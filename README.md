# grid-layout

SCSS-mixin for creating grid layouts.

## HTML

```html
<h2>Example (xof24)</h2>
<div class="cols24">
  <div class="col c8of24">&nbsp;</div>
  <div class="col c8of24">&nbsp;</div>
  <div class="col c8of24">&nbsp;</div>
</div> <!-- cols -->

<h2>Columns with offset (xof24)</h2>
<div class="cols24">
  <div class="col c8of24 offset8of24">&nbsp;</div>
  <div class="col c8of24">&nbsp;</div>
</div> <!-- cols -->

<h2>Columns with offset (xof24)</h2>
<div class="cols24">
  <div class="col c4of24">&nbsp;</div>
  <div class="col c16of24 offset4of24">&nbsp;</div>
</div> <!-- cols -->

<h2>Columns with offset (xof24)</h2>
<div class="cols24">
  <div class="col c4of24">&nbsp;</div>
  <div class="col c4of24">&nbsp;</div>
  <div class="col c4of24">&nbsp;</div>
  <div class="col c6of24 offset6of24">&nbsp;</div>
</div> <!-- cols -->

<h2>Second set of columns (xof12)</h2>
<div class="cols12">
  <div class="col c4of12">&nbsp;</div>
  <div class="col c8of12">&nbsp;</div>
</div> <!-- cols -->

<h2>Second set of columns (xof12)</h2>
<div class="cols12">
  <div class="col c8of12 offset4of12">&nbsp;</div>
</div> <!-- cols -->
```

## SCSS

### Default

```scss
/*
Generates a grid that has 24 columns with a 20px
margin at 960px width
*/

@include grid-layout();
```

### Advanced

```scss
/*
Generates a grid that has 24 columns with a 10px
margin at 1020px width
*/

@include grid-layout(24, 1020px, 10px);
```

## Installation

```shell
bower install grid-layout
```
