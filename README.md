# px-list-bare-design

The Predix UI List Bare module simply removes bullets and indents from lists. This module is a fork of the [inuitcss list-bare module](https://github.com/inuitcss/objects.list-bare).

## Dependencies

The `px-list-bare-design` module depends on one other Px module:

* [px-defaults-design](https://github.com/PredixDev/px-defaults-design)

## Upstream dependency

The `px-list-bare-design` module is also an upstream dependency in this meta kit:

* [px-meta-lists-design](https://github.com/PredixDev/px-meta-lists-design)

## Installation

Install this module and its dependencies using bower:

    bower install --save px-list-bare-design

Once installed, `@import` into your project's Sass file in its **Objects** layer:

    @import "px-list-bare-design/_objects.list-bare.scss";

## Usage

Basic usage of the `px-list-bare-design` module uses one required class:

    <ul class=list-bare>
        <li>Foo</li>
        <li>Bar</li>
        <li>Baz</li>
    </ul>

The only valid children of the `.list-bare` node are `<li>`s.

View the full API [here](https://predixdev.github.io/px-list-bare-design/).
