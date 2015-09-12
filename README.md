# Wrapper

The `wrapper` object will wrap its content up to the defined width.

## Dependencies

The `wrapper` object depends on two other modules:

* [settings.defaults](https://github.com/treeframework/settings.defaults)
* [tools.functions](https://github.com/treeframework/tools.functions)

If you install the `wrapper` object using Bower or npm, you will get these 
dependencies at the same time. If not using Bower or npm, please be sure to 
install and `@import` these dependencies in the relevant way.

## Installation

You can install the `wrapper` module via Bower, npm, or copy and paste.

### Install using Bower:

```sh
$ bower install tree-wrapper --save
```

Once installed, `@import` into your project in its Objects layer:

```scss
@import "bower_components/tree-wrapper/object.wrapper";
```

### Install using npm:

```sh
$ npm install tree-wrapper --save
```

### Install via file download

The least recommended option for installation is to simply download
`_object.wrapper.scss` into your project and `@import` it into your project in
its Objects layer.

## Usage

Basic usage of the `wrapper` object uses the required classes:

```html
<div class="o-wrapper">...</div>
```

## Options

To turn responsive feature on, set switch to true (before you `@import` the file):

```scss
$tree-enable-wrapper--responsive:    true;
@import "bower_components/tree-wrapper/object.wrapper";
```

## Credits

* **[inuitcss](https://github.com/inuitcss)** Powerful, Sass-based, OOCSS
framework designed with scalability and performance in mind.
