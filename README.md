#&lt;ninja-presentation&gt;

A kit of Web Components wrappers to easily build a web based slideshow on Google Chrome.
Attribute names are similar to the css properties. It is not an accident ;)

Do not be fooled. You do not have to be a ninja to use it! Let the tool work for you.

> [See the demo](http://viniciusalmeida.github.io/ninja-presentation/#1) and do not forget to see [your code](https://github.com/viniciusalmeida/ninja-presentation/blob/gh-pages/index.html).

> A [real presentation](http://viniciusalmeida.github.io/presentations/introducing-the-gruntjs) using ninja-presentation

##Usage

Import the [Polymer](http://www.polymer-project.org/) on your page:
```html
<script src="//cdnjs.cloudflare.com/ajax/libs/polymer/0.0.20130816/polymer.min.js"></script>
```

Import the custom element:
```html
<link rel='import' src='src/ninja-presentation.html'>
```

Start the markup of you presentation:
```html
<ninja-presentation>
	<slide>
		<h1>Is very simple, huh?</h1>
	</slide>
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

###&lt;slide&gt; options

|Attribute|Options|Description|
|:--------|:------|:----------|
|`background`|*string*|The background on the slide - Any value accepted by the CSS background property|
|`font`|*string*|The font-family of the texts on the slide|
|`color`|*string*|The font color of the texts on the slide|
|`align`|*string*|The align of the texts on the slide|

###Fragmented slide elements

To use this feature simply set ```class='fragment'``` on the necessary elements.

---

Look this [yeoman generator](https://github.com/rafinskipg/generator-webcomponents/).

---

@ works on Chrome

*Made by [@vimoding](https://twitter.com/vimoding)*
