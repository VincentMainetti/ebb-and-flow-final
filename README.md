# ebb-and-flow-final
<!DOCTYPE html>
<html dir="ltr" lang="en">
<head>
	<meta charset="utf-8">
	<link href="css/main.css" rel="stylesheet"><!-- this is an external css, the best practice -->
	<link href="css/print.css" media="print" rel="stylesheet"><!-- media query inside of a link element -->
	<title>The Dao of Web Design / Summary of</title>
	<meta content="Vincent Mainetti" name="author">
</head><!-- Summary in markdown to HTML, this is how to write a note -->
<body>
	<header class="title">
		<figure class="graphic" id="hero-image">
			<img alt="a monitor with smartphones on either side all displaying a yin and yang symbol" src="img/hero-image-2.svg" srcset="img/hero-image-2.svg">
			<figcaption class="credit">
				Artwork by <a href="#vincent-mainetti">Vincent Mainetti</a>
			</figcaption>
		</figure><!-- watch the tags -->
		<h1 class="summary">A Summary of <cite>A Dao of Web Design</cite></h1>
		<p class="byline">By <a href="#vincent-mainetti">Vincent Mainetti</a> ☯ September 10, 2017</p>
	</header>
	<main class="margin-offset">
		<p>As a whole we tend to treat new mediums in the manner we handle the most closely related existing familiar medium. Such was the case with the web being treated like paper.In reality the web is constantly <s>changing</s> evolving, and we as designers should do our best to compliment this attribute of the web. <b>Content must come first, and accessibility with adaptability must be emphasized explicitly.</b></p>
	</main>
	<p class="full">Traditionally designers used <abbr title="hyperstext markup language">HTML</abbr> to create web pages, but now HTML is used for the frame work of a page and <abbr title="cascading style sheets">CSS</abbr> to suggest the appearance. By doing this it allows for the web browsers to read, and display the web pages even if there are elements or aspects that are not recognized. The advantage in designing web pages this way is increased functionality across different browsers, operating systems, and devices. Not everyone has optimal vision, and some may need to increase font size to read web pages. Some may be color blind, and need the emphasized words to read as emphasized without with use of color. A good way to remember this is that function is more important than aesthetic.</p>
	<p class="full">Throughout the article, Allsopp give a few tips to the reader on what can be done to increase the adaptability and accessibility of web pages. The most important in these tips is for designers to stop trying to “control” the web, rather let the web respond to direction. Avoid absolute values, such as point size for fonts, instead let the viewer changes the font to the appropriate size for their needs. If a specific size difference between a header, footer, or body text is desired try using proportional sizing. Proportional sizing methods can be used to suggest the size of margins, and images also. If a designer is still concerned about “exactly how” a page look then they have not yet grasped this concept.</p><!-- <figure class="quote">
    <blockquote cite="https://alistapart.com/article/dao"><p>“Flow like water”</p></blockquote>
    <figcaption>-John Allsopp-</figcaption>   <!- figcaption is optional ->
  </figure> -->
	<p class="full">Read The Full Article <a href="https://alistapart.com/article/dao">A Dao of Web Design</a> By <a href="https://alistapart.com/article/dao">John Allsopp</a> • <time datetime="2017-09-10">April 07, 2000</time></p><!-- attributes must be quoted  date is an attribute-->
	<section class="author margin-offset" id="vincent-mainetti">
		<h2>About the Author</h2><!-- don't forget the id selector, only one per page -->
		<div class="bio">
			<figure class="headshot">
				<img alt="Aphotograph of the author holding a camera, and looking stoic" class="me" src="img/headshot.png">
			</figure>
			<h3>Vincent Mainetti</h3>
			<p>At a young age, I discovered a strong interest in papers, pencils and pens. This interest quickly developed into a love for the arts. I spent most of my young life drawing as much as I could, and learned that art provided me a level of enjoyment I couldn’t find elsewhere. As I grew older my interests migrated towards technology, and I found myself spending time navigating this new online world. Eventually I found myself with an Associate’s degree in art studies, it was at that point that I realized that I wanted to do more than just study the arts. I wanted to create using the technology that enticed me as a child. Graphic design was the perfect combination of the arts and technology, and in 2015 I began my journey towards becoming a designer. I enrolled at my local community college with the goal of a second Associate’s degree. I graduated in 2017 with several academic awards, and am now pursuing a Bachelor’s of Fine Arts at Montserrat College of Art.</p>
		</div>
	</section>
	<footer>
		<div style="margin-left: 2em">
			index
		</div>
		<ul>
			<li>
				<a href="h1">Artwork</a>
			</li>
			<li>
				<a href="summary">Summary</a>
			</li>
			<li>
				<a href="vincent-mainetti">about the author</a>
			</li>
		</ul>
	</footer>
</body>
</html>
