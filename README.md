!DOCTYPE html>
<html>
<head>
	<title>First Webpage</title>
<link rel="stylesheet" href="styles.css">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link href="https://fonts.googleapis.com/css?family=Noto+Sans|Roboto+Mono&display=swap" rel="stylesheet">
</head>
<body>
	<div class="container">
	<div class="intro">
	<img class="profile-picture"; src="images/profile-picture.jpg"/>
	<h1> Ailidh Kinney </h1>
	<h3> Trainee Web Developer</h3>
	<p class="quote">"Do what you love and you'll never work a day in your life."</p>
</div>
<hr>
<div class="about-grid">
	<div class="i-am">
		<h3> I am</h3>
		<ul class="about-list">
			<li>A dog and cat mum</li>
			<li>A scheduler with BBC</li>
		</ul>
	</div>
	<div class="i-like">
		<h3> I like to</h3>
		<ul class="about-list">
			<li>Play with my pets</li>
			<li>Watch youtube videos</li>
		</ul>
	</div>
</div>
<div>
	<hr>
	<h3 class="projects-heading"> My Projects</h3>
	<div class="projects-grid">
	<div class="project-image-wrapper">
		<h4> Project 1</h4>
		<img class="project-image" src="images/project-1.jpg"/>
	</div>
	<div class="project-image-wrapper">
		<h4> Project 2</h4>
	<img class="project-image" src="images/project-2.jpg"/>
</div>
<div class="project-image-wrapper">
	<h4>Project 3</h4>
	<img class="project-image" src="images/project-3.jpg"/>
</div>
<div class="project-image-wrapper">
	<h4>Project 4</h4>
	<img class="project-image" src="images/project-4.jpg"/>
</div>
</div>
</div>
<div class="links-and-contact">
	<div class="links">
	<h3> Links</h3>
	<ul class="links-list">
		<li>
			<a href="https://twitter.com/hihelloimailidh"> Twitter </a>
		</li>
		<li>
			<a href="https://Linkedin.com/in/ailidkinney"> Linkedin </a>
		</li>
	</ul>
</div>
<div>
	<form action="#">
		<label for="email">
			<h4>Email</h4>
			<input type="email" id="email" placeholder="Enter your email"/>
		</label>
		<label for="message">
			<h4>Message</h4>
			<textarea id="message">Your Message</textarea>
		</label>
		<div class=submit-button-wrapper">
			<input type="submit" value="Send Message" id="submit-button"/>
	</form>
</div>
</div>
</div>
<script src="script.js"></script>
</body>
</html>
