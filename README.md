# Makeup

Curated collection of jQuery plugins for common accessibility patterns.

* [jquery-next-id](https://github.com/ianmcburnie/jquery-next-id)
* [jquery-focusable](https://github.com/ianmcburnie/jquery-focusable)
* [jquery-focus-exit](https://github.com/ianmcburnie/jquery-focus-exit)
* [jquery-mouse-exit](https://github.com/ianmcburnie/jquery-mouse-exit)
* [jquery-common-keydown](https://github.com/ianmcburnie/jquery-common-keydown)
* [jquery-prevent-scroll-keys](https://github.com/ianmcburnie/jquery-prevent-scroll-keys)
* [jquery-linear-navigation](https://github.com/ianmcburnie/jquery-linear-navigation)
* [jquery-roving-tabindex](https://github.com/ianmcburnie/jquery-roving-tabindex)
* [jquery-active-descendant](https://github.com/ianmcburnie/jquery-active-descendant)
* [jquery-keyboard-trap](https://github.com/ianmcburnie/jquery-keyboard-trap)
* [jquery-screenreader-trap](https://github.com/ianmcburnie/jquery-screenreader-trap)

Experimental:

* [jquery-button-flyout](https://github.com/ianmcburnie/jquery-button-flyout)
* [jquery-link-flyout](https://github.com/ianmcburnie/jquery-link-flyout)
* [jquery-menu](https://github.com/ianmcburnie/jquery-menu)
* [jquery-tabs](https://github.com/ianmcburnie/jquery-tabs)
* [jquery-dialog](https://github.com/ianmcburnie/jquery-dialog)
* [jquery-tooltip](https://github.com/ianmcburnie/jquery-tooltip)
* [jquery-stick](https://github.com/ianmcburnie/jquery-stick)

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
