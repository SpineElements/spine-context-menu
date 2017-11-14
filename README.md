# \<spine-context-menu\>

An element to provide a contextual menu with fully customizable trigger and content.
The element is able to adjust its drop-down menu position in the case when the
drop-down is popping up outside of the viewport borders.

The properties `verticalOffset` and `horizontalOffset` allows customizing pop-up
vertical and horizontal position.

This element extends [`vaadin-context-menu`](https://github.com/vaadin/vaadin-context-menu)
enhancing its positioning and keyboard control.

This element is intended to handle the stacking contexts problem
(for details see GitHub [issue](https://github.com/PolymerElements/paper-menu-button/issues/9#issuecomment-199478430),
and [PR](https://github.com/PolymerElements/iron-overlay-behavior/pull/155)).

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your element locally.

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
