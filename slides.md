# Angular.js in simple words


<!-- # Video

  <video data-autoplay>
    <source data-src="https://s3.amazonaws.com/static.slid.es/site/homepage/v1/homepage-video-editor.mp4" type="video/mp4" />
  </video> -->
# Customize

Transition Styles: [None](?transition=none#/transitions) -
[Slide](?transition=slide#/transitions) -
[Convex](?transition=convex#/transitions) -
[Concave](?transition=concave#/transitions) -
[Zoom](?transition=zoom#/transitions)

Themes: <a href="#" onclick="document.getElementById('theme').setAttribute('href','node_modules/reveal.js/css/theme/black.css'); return false;">Black (default)</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','node_modules/reveal.js/css/theme/white.css'); return false;">White</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','node_modules/reveal.js/css/theme/league.css'); return false;">League</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','node_modules/reveal.js/css/theme/sky.css'); return false;">Sky</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','node_modules/reveal.js/css/theme/beige.css'); return false;">Beige</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','node_modules/reveal.js/css/theme/simple.css'); return false;">Simple</a> <br>
<a href="#" onclick="document.getElementById('theme').setAttribute('href','node_modules/reveal.js/css/theme/serif.css'); return false;">Serif</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','node_modules/reveal.js/css/theme/blood.css'); return false;">Blood</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','node_modules/reveal.js/css/theme/night.css'); return false;">Night</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','node_modules/reveal.js/css/theme/moon.css'); return false;">Moon</a> -
<a href="#" onclick="document.getElementById('theme').setAttribute('href','node_modules/reveal.js/css/theme/solarized.css'); return false;">Solarized</a>

Highlight: <a href="#" onclick="document.getElementById('highlight').setAttribute('href','node_modules/reveal.js/lib/css/zenburn.css'); return false;">Zenburn</a> -
<a href="#" onclick="document.getElementById('highlight').setAttribute('href','node_modules/base16-oceanic-next/highlight.js/base16-oceanicnext.dark.css'); return false;">Oceanic Next (default)</a> -
<a href="#" onclick="document.getElementById('highlight').setAttribute('href','node_modules/highlight.js/src/styles/default.css'); return false;">default</a> -
<a href="#" onclick="document.getElementById('highlight').setAttribute('href','node_modules/highlight.js/src/styles/github.css'); return false;">github</a>


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

https://github.com/johnpapa/angular-styleguide


# Questions?
