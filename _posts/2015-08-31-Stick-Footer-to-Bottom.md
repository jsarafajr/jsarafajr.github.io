---
layout: post
title: How to stick footer with CSS
published: true
---

Next example shows an easiest way to stick your footer to bottom of a page using CSS.  

### HTML

```html
<html>
<body>
	<div class="header"></div>
    <div class="container"></div>
    <div class="footer"></div>
</body>
</html>
```

### CSS

```css
html {
	position: relative;
	min-height: 100%;
}

body {
	margin-bottom: 150px; // 150px = footer height
}

.footer {
	position: absolute;
    bottom: 0;
    height: 150px;
    width: 100%
}
```
