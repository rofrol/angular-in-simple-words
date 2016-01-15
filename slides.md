# Angular.js in simple words

# HTML tags

Angular is a way to add new html tags

# Tags are declarative

You specify what you want not how to do it

# Cons?

# if and loop in templates :(

# if and loop in templates :(

- ng-if
- ng-repeat

# Simple example

index.html
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
<script src="app.js"></script>
```

# I want my javascript back!

app.js
```javascript
angular.module('myApp', []).
controller('myController', function() {
  console.log('Hello console');
});
```

# Services are singletones

# Three kinds of services

- factory
- provider
- config

# Three kinds of services

- factory - without new
- provider - with new
- config - new but configure before

# Data binding

# Two-way data-binding

# One source of true

# Scope

# Dirty checking

# Directives

# config

# Injecting

inversion of control -> decoupling -> components

# Kinds of Scope

# ng-if and ng-repeat have their own scopes

# Testing

# Local storage

Example from angularity-todo-es5

# Digest

# Talking to outside world

# Learn

- free video course
- oficial turorial

# Style guide

John Papa on github

# About me

# Questions
