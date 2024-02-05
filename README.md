
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="styles.css">
    <title>Main Page</title>
</head>

<body>
									<!-- Header -->
	<section class='header'>
     <div class="outer-nav">
	   <nav class="navtab">
         <a href="#home" class="active">Home</a>&nbsp;&nbsp;
         <a href="#places">Regions</a>&nbsp;&nbsp;
         <a href="history.html">History</a>&nbsp;&nbsp;
		</nav>
	</div>
	</section>
	
   
									<!-- Intro Video and Title -->
	<section class='video_main' id="home">
		<video autoplay loop muted plays-inline class="main_video">
			<source src="images/videomain.mp4" type="video/mp4"/>
		</video>
		<div class="video_main_text">
		<span><h1 class="pagetitle">Love the Philippines</h1></span>
		</div>
	</section>

									<!-- Brief Intro -->
	<section class='brief_intro' id="intro">
		<div class='intro_text'>
		<p>Embark on a journey through the heart of the Philippines, where the beauty of Luzon, Visayas, and Mindanao awaits your exploration. In Luzon, be captivated by the bustling energy of Manila and the serene landscapes of Banaue's rice terraces. Venture to the Visayas region and find yourself enchanted by the white sandy beaches of Boracay and the historical charm of Cebu. Head down to Mindanao, where vibrant cultures and lush landscapes merge seamlessly. From the enchanting Enchanted River to the picturesque landscapes of Surigao, each region tells a unique story. Join us on an adventure that spans across these diverse islands, and discover the rich tapestry that makes the Philippines truly extraordinary.</p>
		</div>
	</section>
			
			<br><br>
			<h1 class="region_title" id="places">Explore the Major Island Groups of the Philippines</h1>
	
									<!-- Clickable Regions -->
	<section class='regions'>
		<div class='spec_regions'>
			<div><a href="luzon.html"><img class='reg' src='images/luzon.png'></a></div>
			<div><a href="visayas.html"><img class='reg' src='images/visayas.png'></a></div>
			<div><a href='mindanao.html'><img class='reg' src='images/mindanao.png'></a></div>
		</div>
	</section>


									<!-- Footer -->
	<br><br><br><br>
	
	<footer>
	<div class='con-footer'>
	<nav>
	  <div class="shortcut">
		<ul>
				<li><h3>Quick Links</h3></li>
				<li><a href="#home">Back to Top</a></li>
				<li><a href="#intro">About</a>
				<li><a href="#places">Places</a></li>
				<li><a href="history.html">History</a>
		</ul>
	  </div>
	  </nav>
		
	<div class="subscribe">
		<h3>Newsletter</h3>
		<div>
		  <input type="email" placeholder="Please input your email address" />
		  <button class='b_footer'>Subscribe</button>
		</div>
	</div>

  </div>
  </footer>




	
</body>

</html>
