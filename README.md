# Learn to Code
Workshop from 10/3/2016

> Taught by James Traver ([@code4coffee](https://twitter.com/code4coffee), jamest@ga.co)

## HTML Tags

Parent Tag > Child Tag
`html` > `body` > `section`
`ul` > `li`


```html
<html> - this encompasses the entire document
	<head> - this contains header/meta data
		<title> - for your web browser's window
		<meta> - to describe your webpage
		<link> - css/stylesheets
		<script> - javascripts
	<body>
		<header> - logo, content about page
		<nav> - navbar or navigation links
		<section> - sections of content (replace divs)
			<articles> - children of sections, aka blog posts, jobs, etc
		<footer> - guess what goes here?
		<div> - divided section on a page
		<em> - italic aka emphasized text
		<strong> - bold aka STRONG text
		<h1> through <h6> - headers!
		<p> - lorem ipsum whatever
		<img> - for images (mainly cats and dogs)
		<picture> - for responsive/retina imgs (new)
		<audio> - for audio files to be played
		<video> - for videos
		<hgroup> - group headers
		...a lot more
```


#### Links

- [Intro to Modern Computer Science Slide Deck](https://prezi.com/lxsmeaue4mda/intro-to-modern-computer-science/)
- [Samuel L. Ipsum](http://slipsum.com/)
- [Ariane 5 Explosion](https://www.youtube.com/watch?v=kYUrqdUyEpI)

#### Source Code

##### HTML

```html
<!DOCTYPE html>
<html>
<head>
	<title>James' Portfolio</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<h1>James</h1>
	<p>jamest@ga.co<br>
	http://codeforcoffee.org<br>
	@code4coffee
	</p>
	<h1>Objective/Goal/World Domination</h1>
	<p>
	My goal is to be awesome and make life fun.</p>

	<h1>Experience</h1>

	<h3>Web/Android Lead Instructor at General Assembly</h3>
	<p>
		<strong>Chicago, IL</strong><br>
		<em>January 2015 through present</em><br>
		My job duties are to never leave the building, water the plants, and teach. 
	</p>

	<h3>Title</h3>
	<p>
		<strong>Chicago, IL</strong><br>
		<em>June 2008 through present</em><br>
		Pay the bills. Pay the bills. Pay the bills. Pay the bills. Pay the bills. Pay the bills. Pay the bills. Pay the bills. Pay the bills. Pay the bills. Pay the bills. Pay the bills. Pay the bills. 
	</p>

	<h1>Skills</h1>
	<p>Technical Abilities
		<ul>
			<li>HTML</li>
			<li>CSS</li>
			<li>Being awesome</li>
		</ul>
	</p>

</body>
</html>
```

##### CSS 

```css
/* i can leave comments like this */
/* my first selector */

/* look good on every device */
body {
	font-size: 14px;
	margin-left: 2rem;
	margin-right: 2rem;
	color: purple; /* names, hex codes, rgb, etc */
	/*background: tan;*/
}
h1 {
	/*font-size: 12px;*/
	font-size: 2rem; /* 300% of body's font-size */
}
h3 {
	font-size: 1.5rem; /* 150% of body's font-size */
	margin-top: 0px;
	margin-bottom: 0px;
}
p {
	font-size: 1rem; /* 100% of body's font-size */
}
```
