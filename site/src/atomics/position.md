---
title: Position Atomics
description: Position related atomic css classes for the Atlas Design System
template: standard
---

# Position Atomics

These classes can be used to help us place elements outside of the typical document flow. Side related classes can be used in conjunction with margin to space things more precisely.

## Available classes

```Text
.position-fixed
.position-relative
.position-absolute
.position-sticky

.position-fixed-tablet
.position-relative-tablet
.position-absolute-tablet

.top-0
.right-0
.left-0
.bottom-0
```

## Example

Here we place an element in the bottom right corner of another element.

```html
<div class="position-relative background-color-primary padding-xl">
	<span class="position-absolute bottom-0 right-0 color-primary-invert margin-sm">
		Absolutely
	</span>
</div>
```
