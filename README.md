### Accrue.js

A loan and interest calculation plugin for jQuery.

*****

### What You Need

The only file you need (besides a jQuery library) is jquery.accrue.min.js. The included css file is only for the example page. The intent is that you specify your own styles, and it will be nice that you don't have to override any of my crap. :)

*****

### Usage

For the most basic usage of the plugin, all you need is the code below. Of course, you may need to adjust src properties based on where you store files, and you'll want to add styles - but the core functionality will be there.

```html
<div class="calculator"></div>
<script src="http://code.jquery.com/jquery-1.10.1.min.js"></script>
<script src="jquery.accrue.min.js"></script>
<script>
$(document).ready(function(){
	$(".calculator").accrue();
});
</script>
```

#### [View Demos](http://accruejs.com)
#### [Documentation](https://github.com/jpederson/Accrue.js/wiki)
