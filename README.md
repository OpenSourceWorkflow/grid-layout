grid-layout
===========

scss mixin for creating grid layouts

Docs
----

```scss
grid-layout($columns: 24, $sitewidth: 960, $margin: 20)
```

Usage Examples
--------------

Plain:
```scss
@include grid-layout();
```

Advanced:
```scss
/*
generates a grid that has 24 columns with a 10px
margin at 1020px width
*/

@include grid-layout(24, 1020, 10);
```

Installation
------------

```shell
bower install markusfalk/grid-layout
```
