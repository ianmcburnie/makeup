# Makeup

Curated collection of experimental jQuery plugins for common accessibility patterns.

* [jquery-active-descendant](https://github.com/ianmcburnie/jquery-active-descendant)
* [jquery-click-flyout](https://github.com/ianmcburnie/jquery-click-flyout)
* [jquery-common-keydown](https://github.com/ianmcburnie/jquery-common-keydown)
* [jquery-focusable](https://github.com/ianmcburnie/jquery-focusable)
* [jquery-focus-exit](https://github.com/ianmcburnie/jquery-focus-exit)
* [jquery-focus-flyout](https://github.com/ianmcburnie/jquery-focus-flyout)
* [jquery-grid-navigation](https://github.com/ianmcburnie/jquery-grid-navigation)
* [jquery-hover-flyout](https://github.com/ianmcburnie/jquery-hover-flyout)
* [jquery-keyboard-trap](https://github.com/ianmcburnie/jquery-keyboard-trap)
* [jquery-linear-navigation](https://github.com/ianmcburnie/jquery-linear-navigation)
* [jquery-mouse-exit](https://github.com/ianmcburnie/jquery-mouse-exit)
* [jquery-next-id](https://github.com/ianmcburnie/jquery-next-id)
* [jquery-prevent-scroll-keys](https://github.com/ianmcburnie/jquery-prevent-scroll-keys)
* [jquery-roving-tabindex](https://github.com/ianmcburnie/jquery-roving-tabindex)
* [jquery-screenreader-trap](https://github.com/ianmcburnie/jquery-screenreader-trap)
* [jquery-skip-to](https://github.com/ianmcburnie/jquery-skip-to)

Highly Experimental:

* [jquery-dialog](https://github.com/ianmcburnie/jquery-dialog)
* [jquery-hijax-button](https://github.com/ianmcburnie/jquery-hijax-button)
* [jquery-menu](https://github.com/ianmcburnie/jquery-menu)
* [jquery-tabs](https://github.com/ianmcburnie/jquery-tabs)
* [jquery-tooltip](https://github.com/ianmcburnie/jquery-tooltip)

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
