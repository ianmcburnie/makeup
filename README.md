# Makeup

Collection of jQuery plugins for common accessibility patterns.

* [jquery-next-id](https://github.com/ianmcburnie/jquery-next-id)
* [jquery-focus-exit](https://github.com/ianmcburnie/jquery-focus-exit)
* [jquery-mouse-exit](https://github.com/ianmcburnie/jquery-mouse-exit)
* [jquery-common-keydown](https://github.com/ianmcburnie/jquery-common-keydown)
* [jquery-common-keys](https://github.com/ianmcburnie/jquery-common-keys)
* [jquery-roving-tabindex](https://github.com/ianmcburnie/jquery-roving-tabindex)
* [jquery-active-descendant](https://github.com/ianmcburnie/jquery-active-descendant)
* [jquery-focusable](https://github.com/ianmcburnie/jquery-focusable)
* [jquery-prevent-document-scroll-keys](https://github.com/ianmcburnie/jquery-prevent-document-scroll-keys)
* [jquery-keyboard-trap](https://github.com/ianmcburnie/jquery-keyboard-trap)
* [jquery-screenreader-trap](https://github.com/ianmcburnie/jquery-screenreader-trap)

## Development

No actual development happens in this repo. It is simply a collection of git submodules.

Every time a submodule receives an update, we need to run through the following steps:

* Run `git submodule update --remote --merge` to update all submodules to latest commit
* Run `npm version patch|minor|major` to increment package version and create git tag
* Run `git push` to commit changes to GitHub
* Run `git push origin vX.X.X` to push tag to GitHub
* Run `npm publish` to publish package to NPM

To add a new submodule, run `git submodule add https://github.com/theorg/theproject` in the project root directory.
