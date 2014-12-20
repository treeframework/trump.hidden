# Hidden

The `hidden` module simply hides content.

## Dependencies

The Hidden module depends on one other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)

If you install the Hidden module using Bower, you will get these dependencies at
the same time. If not using Bower, please be sure to install and `@import` these
dependencies in the relevant way.

## Installation

The recommended installation method is Bower, but you can install the Hidden
module via a Git Submodule, or copy and paste.

### Install using Bower:

```sh
$ bower install --save tree-hidden
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "bower_components/tree-hidden/trump.hidden";
```

### Install as a Git Submodule:

```sh
$ git submodule add git@github.com:treeframework/trump.hidden.git
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "trump.hidden/trump.hidden";
```

### Install via file download

The least recommended option for installation is to simply download
`_trump.hidden.scss` into your project and `@import` it into your project
in its Trump layer.

## Usage

Basic usage of the Hidden module uses the required classes:

```html
<ul class="hidden">
    <li>Foo</li>
    <li>Bar</li>
    <li>Baz</li>
</ul>
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
