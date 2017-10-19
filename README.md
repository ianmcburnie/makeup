# makeup-ebay (DEPRECATED)

The `makeup-ebay` package is **deprecated**. It has been renamed to `makeup-jquery`. Please update your package dependency references in order to ensure latest updates.

## Description

Curated collection of experimental jQuery plugins for common accessibility patterns.

* [jquery-active-descendant](https://github.com/makeup-jquery/jquery-active-descendant)
* [jquery-common-keydown](https://github.com/makeup-jquery/jquery-common-keydown)
* [jquery-focusable](https://github.com/makeup-jquery/jquery-focusable)
* [jquery-focus-exit](https://github.com/makeup-jquery/jquery-focus-exit)
* [jquery-grid-navigation](https://github.com/makeup-jquery/jquery-grid-navigation)
* [jquery-keyboard-trap](https://github.com/makeup-jquery/jquery-keyboard-trap)
* [jquery-linear-navigation](https://github.com/makeup-jquery/jquery-linear-navigation)
* [jquery-mouse-exit](https://github.com/makeup-jquery/jquery-mouse-exit)
* [jquery-next-id](https://github.com/makeup-jquery/jquery-next-id)
* [jquery-prevent-scroll-keys](https://github.com/makeup-jquery/jquery-prevent-scroll-keys)
* [jquery-roving-tabindex](https://github.com/makeup-jquery/jquery-roving-tabindex)
* [jquery-screenreader-trap](https://github.com/makeup-jquery/jquery-screenreader-trap)

Experimental:

* [jquery-click-flyout](https://github.com/makeup-jquery/jquery-click-flyout)
* [jquery-dialog](https://github.com/makeup-jquery/jquery-dialog)
* [jquery-focus-flyout](https://github.com/makeup-jquery/jquery-focus-flyout)
* [jquery-hijax-button](https://github.com/makeup-jquery/jquery-hijax-button)
* [jquery-hover-flyout](https://github.com/makeup-jquery/jquery-hover-flyout)
* [jquery-menu](https://github.com/makeup-jquery/jquery-menu)
* [jquery-skip-to](https://github.com/makeup-jquery/jquery-skip-to)
* [jquery-tabs](https://github.com/makeup-jquery/jquery-tabs)
* [jquery-tooltip](https://github.com/makeup-jquery/jquery-tooltip)

## Install

`npm install makeup-ebay`

## Bundling

This package is configured to work with the <a href="https://github.com/lasso-js/lasso">LassoJS</a> JavaScript module bundler. LassoJS allows you to easily bundle only the plugins that you require into your frontend payload.

Example browser.json:

```js
// browser.json
{
  {
    "dependencies":[
      "makeup-ebay/jquery-focusable",
      "makeup-ebay/jquery-keyboard-trap",
      "makeup-ebay/jquery-screenreader-trap"
    ]
  }
}
```

Alternatively, to include the entire suite of modules (only recommended for development/prototyping), specify `makeup-ebay`:

```js
// browser.json
{
  {
    "dependencies":[
      "makeup-ebay"
    ]
  }
}
```

## Development / Contributing

No actual development happens in this repo. It is simply a collection of dependencies.
