### Accrue.js

A loan and interest calculation plugin for jQuery.

#### [View Demos](http://accruejs.com)
#### [Documentation](https://github.com/jpederson/Accrue.js/wiki)

*****

![Available on Github](https://img.shields.io/github/release/jpederson/Accrue.js.svg) ![Available on NPM](https://img.shields.io/npm/v/accrue.svg) ![MIT](https://img.shields.io/github/license/jpederson/Accrue.js.svg)

*****

### Quick Start

For the most basic usage of the plugin, all you need is the code below. Of course, you may need to adjust src properties based on where you store files, and you'll want to add styles - but the core functionality will be there.

```html
<div class="calculator"></div>
<script src="//ajax.googleapis.com/ajax/libs/jquery/1.11.1/jquery.min.js"></script>
<script src="jquery.accrue.min.js"></script>
<script>
$(document).ready(function(){
	$(".calculator").accrue();
});
</script>
```

*****

### Install

#### Via Github

```
git clone git@github.com:jpederson/Accrue.js.git accrue.js
```

#### Via NPM

```
npm install accrue
```

#### Via Yarn

```
yarn install accrue
```

*****

### Contributing

To contribute, you'll need [nodejs](http://nodejs.org/) and [Grunt](http://gruntjs.com/) installed. Fork and clone the repo, then visit the directory in the terminal and type `npm install`. After that you can simply run the `grunt` command to watch the files in the project. It'll automatically lint, test, compile, and minify the plugin files so you can just code.

![Built with Grunt](https://img.shields.io/badge/built%20with-grunt-orange.svg)

