# PreventDefaultClick

PreventDefaultClick AngularJS directive allows \<a> links to be opened in another window when ctrl or cmd buttons are pressed while clicking on them. Otherwise, an expression will be evaluated, the same behavior as when using ng-click. The directive is wrapped in a RequireJS module.

## Connect the directive to Angular:
```
//module - reference to an Angular module
module.directive('preventDefaultClick', preventDefaultClick);
```

## In a view:
```
<a href="someurl.com" prevent-default-click="expression_to_evaluate()" target="_blank">link</a>
```