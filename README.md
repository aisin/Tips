# Tips

### Guide

**At first to load jQuery, and enable  Tips plugin：**

```js
$(function(){

	$('.demo1').tips({
		msg: 'This is a demo text.'
	});

	$('.demo2, .demo3').tips({
		skin: 'white',
		msg: ''
	});
});
```