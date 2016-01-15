# Angular.js in simple words

# HTML tags

Angular is a way to add new html tags

# Tags are declarative

You specify what you want not how to do it

# Cons?

# if and loop in templates :(

# if and loop in templates :(

ng-if
ng-repeat

# Simple example

```html
<!doctype html>
<div ng-app>
  <ul>
    <li ng-repeat="1 in 1..10">
      <span ng-if="$index % 2 === 0">even</span>
    </li>
  </ul>
</div>
<script src="angular.js"></script>
```
