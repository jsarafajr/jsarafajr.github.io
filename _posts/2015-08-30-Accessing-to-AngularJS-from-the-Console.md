---
layout: post
title: Accessing to AngularJS from the Console
published: true
---


There are a set of scenarious when you need to get angular variables such as scopes, services, values etc. from the developer's console to debug. 
Angular provide methods to help in doing this.

## angular.element
Angular provide a function [angular.element()](https://docs.angularjs.org/api/ng/function/angular.element) which wraps a raw DOM element or HTML string as a jQuery element (jqLite).  
For example next 2 functions works equally and alerts a message when page loaded:
```javascript
// Angular JS
angular.element(document).ready(function() {
	alert("ready");
})
// jQuery
$(document).ready(function() {
	alert("ready");
});
```