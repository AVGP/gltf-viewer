# \<gltf-viewer\>

Displays a 3D representation of a glTF model, interactive or static. 

## Live demo 

[See the component in action](https://avgp.github.io/gltf-viewer). 

## Usage 

You can us the component by importing it like this:

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

## Running Tests
```
$ polymer test
```

Your application is already set up to be tested via [web-component-tester](https://github.com/Polymer/web-component-tester). Run `polymer test` to run your application's test suite locally.
