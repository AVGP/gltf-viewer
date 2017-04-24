# \<gltf-viewer\>

Displays a 3D representation of a glTF model, interactive or static.

## Live demo

<!--
```
<custom-element-demo height="300">
  <template>
    <link rel="import" href="gltf-viewer.html">
    <gltf-viewer src="demo/duck.gltf" interactive></gltf-viewer>
  </template>
</custom-element-demo>
```
-->
```html
<other-element></other-element>
<my-element></my-element>
```

[See the component in action](https://avgp.github.io/gltf-viewer).

## Usage

Here is a simple sample to get you started:

*Important note:* The example is great to try it out, but you should install the component if you build an application with `<gltf-viewer>` so you don't rely on external sources too much!

```html
<!doctype html>
<html>
<head>
  <!--  polyfill for older browsers -->
  <script src="https://cdnjs.com/webcomponentsjs/webcomponents-lite.js"></script>

  <link rel="import" href="https://avgp.github.io/gltf-viewer/gltf-viewer.html">
</head>
<body>
  <gltf-viewer interactive src="/model.gltf"></gltf-viewer>
</body>
</html>
```

## Installation

The component can be installed via [Bower](https://bower.io):

```bash
bower install gltf-viewer
```

## Browser support & glTF support

The component supports:

* IE10 and up
* Safari (OSX & iOS)
* Opera
* Firefox
* Edge
* Chrome & Android browser from 4.x upwards

The component supports both glTF 1.0 and glTF 2.0 models.

## Contributing

If you think the component is missing something or you found a bug, please submit an issue and/or a pull request!

### Setup for contributing

The easiest way to get going is to install the `polymer-cli`:

```bash
npm install -g polymer-cli
```

Then you can clone this repository to your local computer:

```bash
git clone https://github.com/avgp/gltf-viewer.git
cd gltf-viewer
```
You are now inside your cloned repository.

## Serving the local component

If you have `polymer-cli` installed, go into your clone of this repository and run `polymer serve` in a terminal.
You can access the demos via the URL that will be displayed and use the component locally.

### Running Tests
```
$ polymer test
```

The component uses [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
