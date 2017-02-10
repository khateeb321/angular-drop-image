# angular-drop-image

An [AngularJs](https://github.com/angular/angular.js) directive that allows you to drag and drop images into a certain area.

- angular-drop-image require [ngStorage](https://github.com/gsklee/ngStorage).

# Usage

```html
<html>
  <head>...</head>
  <body ng-app="app">
  
    <div class="content" ng-drop-image ng-model="image.src">
      <img ng-src="image.src" />
    </div>
    
    <script>
      angular.module('app', ['ngDropImage']);
    </script>
    
  </body>
</html>
```


# Install

#### NPM

`npm i --save angular-drop-image`

# License

MIT
