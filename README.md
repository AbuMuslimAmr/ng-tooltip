# ng-tooltip

ng-tooltip is a felxible Angular tooltip with a lot of handy options.

## Why ng-tooltip? ... because it supports:
- multiple tooltips at the same time.
- HTML content
- borders
- great set of flexibility options

## Installation
- bower install ng-tooltip

## Usage

Reference JS and CSS files:
````html
<script type="text/javascript" src="/bower_components/ng-tooltip/tooltip.js"></script>
<link rel="stylesheet" href="/bower_components/ng-tooltip/tooltip.css" />
````

Include ng-tooltip as dependency:
````javascript
// Add ng-tooltip as a dependency to your app
angular.module('your-app', ['ng-tooltip']);
````

Examples:
````html
<!-- Simple Content -->
<div id="title">Title</div>
<tooltip on="hover" handle="title" position="bottom">
  Tooltip simple content
</tooltip>

<!-- HTML Content -->
<div id="another-title">Another Title</div>
<tooltip on="click" handle="another-title" position="right">
  <strong>Html Tooltip Content</strong>
  <br/>
  <p>bla bla bla</p>
</tooltip>
````