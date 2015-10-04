# How to use bower_components in posts/pages on this site
In your index.html file, include this code in the head:

```<script src="bower_components/webcomponentsjs/webcomponents-lite.min.js"></script>```

What this does is enables the use of Polymer web components in your page.  Now you need one more little piece of code:

```<link rel="import" href="path/to/your/element.html">```

This will allow for the use of said element in your webpage.  The way that you use it in your webpage is very similar to a ```<div>``` tag.

Simply call the element with ```<element></element>``` and you're done!  That element from Polymer is now on your page.

# To get more elements you can find them [here](https://elements.polymer-project.org/).
