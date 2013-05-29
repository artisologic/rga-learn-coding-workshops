#Workshop n°4 — CSS: Responsive (media-queries)

##Why?

* We need to be able to display our beautiful sites on any device…
* … in a beautiful way!
* The web landscape has evolved dramatically.
* We even have internet-enabled fridges!
* So what are the tools we have?

***

##How?

* The web is inherently responsive.
* Because it is inherently fluid.
* Think percentage based dimensions.
* Ok, but we need more control!

***

##Enters **media-queries**

* Media-queries are not new!
* We've been using it for years.
* print.css anybody?
* We make use of **media types** and **media features**.
* Either at the stylesheet level, or inline.

***

###Stylesheet level (print example)

```
<link rel="stylesheet" media="print" href="print.css" />
```

###Inline (print example)

```
a { … }

@media print {
	a {
		text-decoration: underline;
	}			
}
```

###Media types
Some media types:

* `@media all`
* `@media screen`
* `@media print`
* `@media handheld`

Some more advanced media types:

* `@media speech`
* `@media braille`
* `@media projection`
* `@media tv`

###Media features
Some media features:

* **width** – `min-width: 800px / max-width: 800px`
* **height** – `min-height: 400px / max-height: 400px`

Some more advanced media features:

* **device-width**
* **device-height**
* **orientation**
* **resolution**
* **aspect-ration**
* **device-aspect-ratio**

###A word on logical operators

* You can use a comma to separate different conditions (**or**):

```
@media (min-width: 700px), (orientation: landscape) { … }
```

* You can use the **and** keywork too:

```
@media handheld and (orientation: landscape) { … }
```

More operators:

* not
* only


***

##Let's take all this and build something, shall we?