### Accrue.js

A loan and interest calculation plugin for jQuery.

#### [View Demos](http://accruejs.com)
#### [Documentation](https://github.com/jpederson/Accrue.js/wiki)

*****

### Quick Start

For the most basic usage of the plugin, all you need is the code below. Of course, you may need to adjust src properties based on where you store files, and you'll want to add styles - but the core functionality will be there.

```html
<div class="calculator"></div>
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script src="jquery.accrue.min.js"></script>
<script>
$(document).ready(function(){
	$(".calculator").accrue({
		//You can change Default currency USD($) by adding the line below with prefered currency prefix
		currencyFormat: GBP
	});
});
</script>
```

*****

### Options
Default currency USD($) in plugin can be changed as you initialize script through JS and provide the currency_symbol options with prefered currency prefix e.g GBP  

```
<script>
$(document).ready(function(){
	$(".calculator-loan").accrue({
		currency_symbol: GBP
	});
});
</script>
```

### Install Methods

##### Via Github

```
git clone git@github.com:jpederson/Accrue.js.git accruejs
```

##### Via NPM

```
npm install accrue
```

##### Via Bower

```
bower install accruejs
```

*****

### Contributing

To contribute, you'll need [nodejs](http://nodejs.org/) and [Grunt](http://gruntjs.com/) installed. Fork and clone the repo, then visit the directory in the terminal and type `npm install`. After that you can simply run the `grunt` command to watch the files in the project. It'll automatically lint, test, compile, and minify the plugin files so you can just code.

[![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)
