---
layout: post
title: Accessing to AngularJS from the Console
published: true
---


There are a set of scenarious when you need to get access to angular variables like scope, services, values etc. from developer's console to debug. 
Angular provide methods to help in doing this.

## angular.element
Angular provide a function [angular.element()](https://docs.angularjs.org/api/ng/function/angular.element) which wraps a raw DOM element or HTML string as a jQuery element (jqLite).  
For example next 2 functions works equal:

```javascript
// Angular JS
angular.element(document).ready(function() {
	console.log("Angular");
})
// jQuery
$(document).ready(function() {
	console.log("jQuery");
});
```