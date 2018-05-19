Component Color Picker for AngularJS 1.3.0
=============

Original Author: Daniel Reznick - vedmack@gmail.com

Updated Author: Let's Comunica - fabio@letscomunica.com.br
 
**LAST VERSION: 0.0.1**

Installation
=====

Install in you angular project:

```bash
  npm install --save git+ssh://git@bitbucket.org/letscomunicadev/angular-lets-colorpicker-component.git#v0.0.1
```

Updates
=====

Made a modification? Test it at least in one project before submiting a version. It still needs unit testing and CI with projects. After everything seems perfectly up-to-date, run the following steps:

1\. Commit and push your updates using Let's Bitbucket credentials

2\. Change and commit a new tag version (always check and update the last version here and in package.json):

```bash
$ git tag -a vX.X.X -m "version_message"
```

3\. Push the new tag version to remote repository:

```bash
$ git push origin vX.X.X  # Version needs to be the same from commit
```

4\. Run npm installation with the newest version:

```bash
  npm install --save git+ssh://git@bitbucket.org/letscomunicadev/angular-lets-colorpicker-component.git#vX.X.X
```

Fork History
=====

### v0.0.1

+ added quantity color options to be displayed.

Description:
=====

The color picker for AngularJS - Native / Simple / Cool. No other dependencies are needed at all.

Features:
=====

- Can extend simple input
- Can replace a div (or any other container) with an inline color picker
- Can replace any HTML element with a cool tiny trigger
- Can color the extended input

Examples:
=====

![Angular color picker in action](../gh-pages/angular-color-picker-in-action.gif "Angular color picker in action")


<input color-picker ng-model="colorValueInput">

<div color-picker ng-model="colorValueInline"></div>

<input color-picker tiny-trigger="true" ng-model="colorValueTinyTrigger">

<input color-picker color-me="true" ng-model="colorValueInputColor">


Usage:
=====

```javascript
angular.module('colorPickerApp', ['colorpicker-dr'])
  .controller('ColorPickerCtrl', ['$scope', function($scope) {
  }]);
```


Available attributes
=====

* tiny-trigger="true": replace any HTML element with a cool tiny trigger
* color-me="true": color the extended input on color selection


Contact/Social:
=====
If you want to ask a question you can post a question on [stackoverflow](www.stackoverflow.com)

If you like my directive, you can show your appreciation by following me on [Twitter](https://twitter.com/danielreznick) / [GitHub](https://github.com/vedmack)


License:
=====

Copyright (c) 2015 Daniel Reznick, released under the MIT license
