#&lt;ninja-presentation&gt;

A kit of Web Components wrappers to easily build a web based slideshow on Google Chrome.
Attribute names are similar to the css properties. It is not an accident ;)

Do not be fooled. You do not have to be a ninja to use it! Let the tool work for you.

> [See the demo](http://viniciusalmeida.github.io/ninja-presentation/#1) and do not forget to see [your code](https://github.com/viniciusalmeida/ninja-presentation/blob/gh-pages/index.html).

##Usage with bower

To install:
```
$ bower install ninja-presentation
```

Import the custom element and your dependencies on your presentation page:
```html
<script type="text/javascript" src="bower_components/platform/platform.js"></script>
<link rel="import" href="bower_components/polymer/polymer.html">
<link rel='import' href='bower_components/ninja-presentation/src/ninja-presentation.html'>
```

##Markup to use the component

Start the markup of you presentation:
```html
<ninja-presentation>
	<ninja-slide>
		<h1>Is very simple, huh?</h1>
	</ninja-slide>
</ninja-presentation>
```

*Maybe you need use a CSS reset. On [example](http://viniciusalmeida.github.io/ninja-presentation) I used the ```*``` selector, but you can use the tool of your preference*

###&lt;ninja-presentation&gt; options

|Attribute|Options|Description|
|:--------|:------|:----------|
|`background`|*string*|The default background of the presentation - Any value accepted by the CSS background property|
|`font`|*string*|The default font-family of the presentation|
|`color`|*string*|The default text color of the presentation|
|`align`|*string*|The default text-align of the presentation|

###&lt;ninja-slide&gt; options

|Attribute|Options|Description|
|:--------|:------|:----------|
|`background`|*string*|The background on the slide - Any value accepted by the CSS background property|
|`font`|*string*|The font-family of the texts on the slide|
|`color`|*string*|The font color of the texts on the slide|
|`align`|*string*|The align of the texts on the slide|

---

Look this [yeoman generator](https://github.com/rafinskipg/generator-webcomponents/).

---

@ works on Chrome

*Made by [@vimoding](https://twitter.com/vimoding)*
