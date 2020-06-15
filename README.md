# Component Color Picker for AngularJS 1.3.0

Original Author: Daniel Reznick - vedmack@gmail.com

Updated Author: Let's Go - contato@letscomunica.com.br
 
## Installation

Install in you angular project:

```bash
$ npm install @letsfullstack/angular-colorpicker-component
```

## Fork History

### v0.0.1

+ added quantity color options to be displayed.

## Description

The color picker for AngularJS - Native / Simple / Cool. No other dependencies are needed at all.

## Features

- Can extend simple input
- Can replace a div (or any other container) with an inline color picker
- Can replace any HTML element with a cool tiny trigger
- Can color the extended input

## Examples

```html
  <input color-picker ng-model="colorValueInput">
  <div color-picker ng-model="colorValueInline"></div>
  <input color-picker tiny-trigger="true" ng-model="colorValueTinyTrigger">
  <input color-picker color-me="true" ng-model="colorValueInputColor">
```

## Usage

```javascript
angular.module('colorPickerApp', ['colorpicker-dr'])
  .controller('ColorPickerCtrl', ['$scope', function($scope) {
  }]);
```

## Available attributes

* tiny-trigger="true": replace any HTML element with a cool tiny trigger
* color-me="true": color the extended input on color selection

## License

Copyright (c) 2015 Daniel Reznick, released under the MIT license
