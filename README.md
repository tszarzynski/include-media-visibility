# include-media-visibility
An include-media plugin for showing / hiding elements based on current active breakpoint

## Introduction
This plugin generates classes for showing/ hiding elements based on current active breakpoint defined by by [include-media](https://github.com/eduardoboucas/include-media).

```scss

@import 'include-media';
@import 'include-media-visibility';

$breakpoints: (phone: 480px, tablet: 768px, desktop: 1024px);

@include im-visibility();
```

####Showing:
Element is **invisible** until 'tablet' breaktpoint is reached.
```html
    <div class="show@tablet"></div>
```

####Hiding:
Element is **visible** until 'tablet' breaktpoint is reached.
```html
    <div class="hide@tablet"></div>
```



## Requirements
* Sass >= 3.4.x
* [include-media](https://github.com/eduardoboucas/include-media)

## Installation
- **Manually:** Download [this file](https://raw.githubusercontent.com/tszarzynski/include-media-grid/master/_include-media-grid.scss) and import it into your Sass project
- **npm:** Run `npm install include-media-grid`

## Author
[Tomasz Szarzynski](http://tmasz.com)
