# YunhoLeeWebsite
<!-- 30MFF Website

Project Name: Daily Water Commercial Film

Concept and Theme: We are promoting our water product that each has its own unique function. We divide water to drink by time of the day (morning, lunch, afternoon, night). In the morning, caffein water is recommended, to wake up ourselves and get ready to start a new day. For lunch, to sustain our body in supreme condition, vitamin water is recommended, which contains crucial vitamins and minerals that helps human metabolism. For evening, charming water is recommended, which contains pleasent scents that relaxes our body after hard work of the day. Finally for night, sleep water is recommended, which helps people to fall asleep. The website is to promote these four types of water products.

Process and Inspiration: I got inspired from a Korean water company website https://www.jpdc.co.kr/samdasoo/index.htm?gclid=EAIaIQobChMIhIqBxcSD9gIVC5BoCR0qmwuLEAAYASAAEgJ4w_D_BwE . In the website, the commercial video is at the most front of the page so that it is very easily accessible. Furthermore, there are tabs that describes more specific about their products, which made it very organised and user-friendly. I decided to implement this method on my website by using a hyperlink between websites. Each websites contain specific contents that are related to each other. As a result, the website exaggerates its contents more efficiently.

Reflection/Evaluation: I have achieved most of the goals. However, there are some ideas that I wish I could add. One of them was the right top tab in the website https://www.jpdc.co.kr/samdasoo/index.htm?gclid=EAIaIQobChMIhIqBxcSD9gIVC5BoCR0qmwuLEAAYASAAEgJ4w_D_BwE . In this website, links of the specifications of their product (origin of the water, history and so on) are organised in 2x2, which is both very accessible and visible. -->

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
