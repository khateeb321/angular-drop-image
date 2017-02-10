# angular-drop-image

Drop Image

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
