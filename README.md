# project-two-template
Project two template for des 341
v<nav>
  <!-- Global naviagtion stuff here, but move this or delete this to your liking. Same goes for the rest -->
  <ul>
    <li><a href="subpage-one.html">example link to subpage one</a></li>
    <li><a href="#">link</a></li>
    <li><a href="#">link</a></li>
  </ul>
</nav>
<main>
  <blockquote>"Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusamus soluta vero fugiat saepe, tempore laboriosam nemo pariatur maxime sunt rerum."</blockquote>
<!-- Main content here -->
  <div class="grid">
    <div>Column 1</div>
    <div>Column 2</div>
  </div>
</main>
<footer>
  <!-- footer content here -->
  &copy; Team Awesome
</footer>
<!-- link for jquery -->
<script
  src="https://code.jquery.com/jquery-3.4.1.min.js"
  integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="
  crossorigin="anonymous"></script>
  <!-- link for your script file -->
  <script src="js/script.js"></script>

  /* Enter your Styles below! */

  body {
  	font-family: Helvetica, sans-serif;
  	font-size: 16px;
  	 }

  h1, h2, h3, h4 {
  	font-family: Helvetica, sans-serif;
  }

  h1 {
  	font-size: 48px;
  }

  h2 {
  	font-size: 36px;
  }

  h3 {
  	font-size: 28px;
  }
  h4 {
  	font-size: 24px;
  }

  blockquote {
  	margin: 20px 60px;
  	font-family: Helvetica, sans-serif;
  }

  header {
  image-align:center;
  	margin-bottom: 20px;}

  /* ensures that your images stretch the width of their containers */
  img { width: 100%; }

  a {
  	color: red;
  	text-decoration: none;
  	 }
  a:hover { color: black; }

  .grid {
  	display: grid;
  	grid-template-columns: 1fr 1fr;
  	grid-gap: 40px;
  	width: 60%;
  	margin: auto;
  }

  .grid div {
  	background-color: #ccc;
  	padding: 20px;
  }

  @media only screen and (min-width:768px) {

  }

  @media only screen and (min-width:1224px) {

  }

  * SUBPAGE ONE *
  
  <!DOCTYPE html>
  <html lang="en">
  <head>
  	<meta charset="UTF-8">
  	<title>Project One - Subpage One</title>
  	<meta name="viewport" content="width=device-width">
  	<link rel="shortcut icon" href="favicon.ico" type="image/x-icon">
  	<link rel="icon" href="favicon.ico" type="image/x-icon">
  	<!-- meyer-reset is a special css library that overrides all the ugle default css styles that come with html5 -->
  	<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css">
  	<link rel="stylesheet" href="css/style.css">
  </head>
  <body>
  	<!-- These semantic tags were added to help you get started but you are very welcome to delete any of them and do your own thing -->
  	<header>
  		<!-- header, h1, logo etc content -->
  		<h1>Your Project Name, or whatever</h1>
  	</header>
  	<nav>
  		<!-- Global naviagtion stuff here, but move this or delete this to your liking. Same goes for the rest -->
  		<ul>
  			<li><a href="#">link</a></li>
  			<li><a href="#">link</a></li>
  			<li><a href="#">link</a></li>
  		</ul>
  	</nav>
  	<main>
  	<!-- Main content here -->
  	</main>
  	<footer>
  		<!-- footer content here -->
  	</footer>
  	<!-- link for jquery -->
  	<script
    	src="https://code.jquery.com/jquery-3.4.1.min.js"
    	integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo="
    	crossorigin="anonymous"></script>
    	<!-- link for your script file -->
    	<script src="js/script.js"></script>
  </body>
  </html>
