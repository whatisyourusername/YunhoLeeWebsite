<html>
<head>
	<title>DailyWater_YunhoLee</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<style>

	* {
	box-sizing: border-box;
	}

	body {
		background-image: url("back.jpg");
	}

	header {
		background-color: rgba(0, 0, 0, 0.5);
		padding: 30px;
		text-align: center;
		font-size: 80px;
		font-style: italic;
		font-family: 'Times New Roman', Times, serif;
		color: white;
	}

	nav {
		float: left;
		width: 30%;
		text-align: left;
		font-size: 62px;
		font-family: 'Times New Roman', Times, serif;
		color: white;
	}

	nav ul {
		background-color: rgba(0, 0, 0, 0.5);
		list-style-type: none;
		padding: 0;
	}

	article {
		padding: 60px;
		float: left;
		width: 70%;
	}

	section::after {
	content: "";
	display: table;
	clear: both;
	}

	footer {
		background-color: rgba(0, 0, 0, 0.5);
		padding: 10px;
		text-align: center;
		color: rgb(139, 214, 228);
		font-size: 50px;
	}

	@media (max-width: 1200px) {
		nav, article {
		  width: 100%;
		  height: auto;
		}
	}

	a:link {
		color: grey;
		background-color: transparent;
		text-decoration: none;
	}

	a:visited {
		color: pink;
		background-color: transparent;
		text-decoration: none;
	}

	a:hover {
		color: red;
		background-color: transparent;
		text-decoration: underline;
	}

	a:active {
		color: white;
		background-color: transparent;
		text-decoration: underline;
	}

	</style>
</head>

<body>

<header>
	Daily Water
</header>

<section>
	<nav>
		<ul>
			<li>Drink Healthy,</li>
			<li>Drink Smart.</li>
			<li style="text-align: center;">
				<img src="bottle.png" type="image/png" width="300">
			</li>
			<li style="text-align: center;"><a href="water.html">4 Types of Water</a></li>
		</ul>
	</nav>
	
	<article>
		<video width="1080" controls>
			<source src="film.mp4" type="video/mp4" alt="commercial video">
			<source src="movie.ogg" type="video/ogg">
		</video>
	</article>

</section>

<footer>
	<a href="sorry.html">Click Here to Purchase Water</a>
</footer>

<footer>
	<a href="teammates.html">Click Here to meet my Teammates</a>
</footer>

</body>
</html>
