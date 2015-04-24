# Hidden

The `hidden` module simply hides content.

## Dependencies

The `hidden` module depends on one other module:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [settings.responsive](https://github.com/treeframework/settings.responsive)
* [tools.responsive](https://github.com/treeframework/tools.responsive)

If you install the `hidden` module using Bower or npm, you will get these 
dependencies at the same time. If not using Bower, please be sure to install 
and `@import` these dependencies in the relevant way.

## Installation

You can install `hidden` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-hidden --save
```

Once installed, `@import` into your project in its Trump layer:

```scss
@import "bower_components/tree-hidden/trump.hidden";
```

### Install using npm:

```sh
$ npm install tree-hidden --save
```

### Install via file download

The least recommended option for installation is to simply download
`_trump.hidden.scss` into your project and `@import` it into your project
in its Trump layer.

## Usage

Basic usage of the `hidden` module uses the required classes:

```html
<ul class="u-hidden">
    <li>Foo</li>
    <li>Bar</li>
    <li>Baz</li>
</ul>
```

To turn responsive feature on, set switch to true (before you `@import` the file):

```scss
$tree-enable-hidden--responsive:    true;
@import "bower_components/tree-hidden/trump.hidden";
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
