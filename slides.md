# Angular.js in simple words


# Video

  <video data-autoplay>
    <source data-src="https://s3.amazonaws.com/static.slid.es/site/homepage/v1/homepage-video-editor.mp4" type="video/mp4" />
  </video>


# Transition Styles

<a href="?transition=none#/transitions">None</a> -
<a href="?transition=fade#/transitions">Fade</a> -
<a href="?transition=slide#/transitions">Slide</a> -
<a href="?transition=convex#/transitions">Convex</a> -
<a href="?transition=concave#/transitions">Concave</a> -
<a href="?transition=zoom#/transitions">Zoom</a>

# Themes

<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/black.css'); return false;">Black (default)</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/white.css'); return false;">White</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/league.css'); return false;">League</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/sky.css'); return false;">Sky</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/beige.css'); return false;">Beige</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/simple.css'); return false;">Simple</a> <br>
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/serif.css'); return false;">Serif</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/blood.css'); return false;">Blood</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/night.css'); return false;">Night</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/moon.css'); return false;">Moon</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','css/theme/solarized.css'); return false;">Solarized</a>


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

$parent.sth


# Testing


# Local storage


Example from angularity-todo-es5


# Digest


# Talking to outside world


# Events - $scope.watch


# Filters


# Phases: link, etc


# $timeout


# Communicate between Directives


# Kinds of Directives


# Two directives on element and private scope


# $destroy


# Learn

- free video course
- oficial turorial


# Style guide

John Papa on github


# About me


# Questions
