#Workshop n°2 — HTML: Content + Semantic

##Content is king.

* Content is 90% of our websites, the rest is just fluff.
* So we need a way to display our content.
* Hang on! We need more.
* Let me rephrase...
* We need a way to ~~display~~ **describe** our content.
* Why?
* Because we need to teach machines what our content is.

***

##Enters **semantic**!

* Still, why do we need to **describe** our content?
* Because without semantic, our content is just random text, without any meaning.
* If we have a way to describe what our content is, we can figure out what it is even without *visulalising/rendering* it (SEO, accessibility, etc)
* So how?

***

##Enters **HTML**!

* HTML is just text with a **.html** extension…
* … with a few rules.
* It is a **markup** language.
* A markup language is made up of a bunch of **tags**.
* Tags may contain other tags.
* Tags may also have **attributes**.

###Minimal structure

```
<!DOCTYPE html>
<html lang="en">
	<head></head>
	<body></body>
</html>
```

###Some tags
Some headings:

* `<h1></h1>`
* `<h2></h2>`
* `<h3></h3>`
* `<h4></h4>`
* `<h5></h5>`
* `<h6></h6>`

A paragraph:

`<p></p>`

An unordered list:

`<ul></ul>`

An ordered list:

`<ol></ol>`

A list element:

`<li></li>`

A link:

`<a href="otherpage.html" title="A link to the other page">Visit other page</a>`

An image:

`<img src="myimage.jpg" alt="A photo of my cat">`

A form:

`<form></form>`

A form input (checkbox):

`<input type="checkbox">`

###Some HTML5 tags
A header:

`<header></header>`

A section:

`<section></section>`

A footer:

`<footer></footer>`

A navigation:

`<nav></nav>`

***

##Let's take all this and build something!