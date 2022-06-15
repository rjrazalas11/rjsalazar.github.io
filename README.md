<!DOCTYPE html>
<html lang="en">
	
	<head>
		<meta charset="utf-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
		<title>My Blog</title>
		<link rel="stylesheet" type="text/css" href="style.css">
	</head>


<body>
	<nav class="navbar">
		<div class="max-width">
		<div class="logo"><a href="#">My<span>Blog</span></a></div>	
		
		<ul class="menu">
			<li><a href="#about">About</a></li>
			<li><a href="#services">Hobbies</a></li>
			<li><a href="#skills">Skills</a></li>
			<li><a href="#contact">Contact</a></li>	
		</ul>
			<div class="menu-btn">
				<img src="images/menu-burger.png">
			</div>
		</div>
	
	</nav>

<!--Home Section-->
	<section class="home" id="home">
		<div class="max-width">
			<div class="home-content">
				<div class="text-1">Hello! Welcome To My Blog</div>
				<div class="text-2">I am Kishes Tamayo</div>
				<div class="text-3">From Muntinlupa City</div>
				<a href="#contact">Check More</a>
			</div>
		</div>
	</section>

<!--About Section-->
	<section class="about" id="about">
		<div class="max-width">
			<h1 class="title">About</h1>
				<div class="about-content">	
				<div class="column left">
					<img src="images/kish6.jpg" alt="Man with Watches"> 
				</div>

				<div class="column right">
					<h2 class="text">
					<p>In the late 1990's, <strong></strong> My Father and my Mother Decided to make a new baby<b>That's why i'm here right now making memories with my classmates </b>. <i>And sharing my life experience and achievement in my early 20's</i>.</p>

			</div>
		</div>
	</div>
	</section>
<!--Services Section-->
	<section class="services" id="services">
		<div class="max-width">
			<h2 class="title">Hobbies</h2>
			<div class="services-content">
				<div class="card">
					<div class="box">
						<img src="images/bad.jpg">
						<div class="text">Badminton</div>
							<p>Badminton is a racquet sport that i played using racquets to hit a shuttlecock across a net.  </p>
					</div>
				</div>

			<div class="card">
					<div class="box">
						<img src="images/alak.jpg">
						<div class="text">Drinking Alcohol</div>
							<p>Drinking Alcohol with my Family & Friends is my Happiness</p>
					</div>
				</div>
			<div class="card">
					<div class="box">
						<img src="images/kanta.jpg">
						<div class="text">Singing</div>
							<p>Singing is my favorite hobby because it helps me to release stress by listening to my own voice</p>
					</div>
				</div>
			</div>
		</div>
	</section>

<!--Skills Section-->
	<section class="skills" id= "skills">
		<h2 class="title">My Skills</h2>
			<div class="max-width">
				<div class="skills-content">
					<div class="column left">
						<div class="text">My Creative Skills & Development Experience</div>
						<p>My skills expertise majors in Web Develoipment using HTML, CSS, JavaScript, PHP and MYSQL which are the primary languages taht power the internet. I'll make sure that your website is up to date and user friendly with simple interface easy to navigate.</p>
						<a href="#">Read More</a>
	</div>
		<div class="column right">
			<div class="bar">
				<div class="info">
					<span>HTML5</span>
					<span>95%</span>
				</div>
				<div class="line HTML5"></div>

			</div>
		<div class="bar">
				<div class="info">
					<span>CCS3</span>
					<span>85%</span>
				</div>
				<div class="line CCS3"></div>

			</div>
		<div class="bar">
				<div class="info">
					<span>JavaScript</span>
					<span>82%</span>
				</div>
				<div class="line JavaScript"></div>
			</div>
		<div class="bar">
				<div class="info">
					<span>PHP</span>
					<span>80%</span>
				</div>
				<div class="line PHP"></div>
			</div>
		<div class="bar">
				<div class="info">
					<span>MYSQL</span>
					<span>80%</span>
				</div>
				<div class="line MYSQL"></div>
			</div>
		
			
		</div>
	</div>
	
	</section>

<!--Contact Section-->
	<section class="contact" id= "contact">
		<div class="max-width">
			<h2 class="title">Contact Us</h2>
			<div class="contact-content">
				<div class="column left">
					<div class="text">Get in Touch Today</div>
			<p>Be the first to know discover how to find the best watch and enjoy exclusive products and offers.
Our customer service team is always happy to hear from you.  you may find all the help you need by following the links below or get in touch with us.. </p>
			<div class="icons">
				<div class="row">
					<img src="images/address-book-solid.svg">
					<div class="info">
						<div class="head">Name</div>
						<div class="sub-title">Kishes Tamayo</div>
					</div>
				</div>

				<div class="row">
					<img src="images/map-marked-alt-solid.svg">
					<div class="info">
						<div class="head">Address</div>
						<div class="sub-title">Muntinlupa, Philippines.</div>
					</div>
				</div>

				<div class="row">
					<img src="images/envelope-open-text-solid.svg">
					<div class="info">
						<div class="head">Email At</div>
						<div class="sub-title">kishes.j.tamayo@gmail.com</div>
					</d
						
				@import url('https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,200;0,300;0,400;0,700;1,400&display=swap');
* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
	text-decoration: none; 
}
.max-width{
	max-width: 1300px;
	padding: 0 80px;
	margin: auto;
}
/*Style for Navigation Bar */
.navbar{
	position: fixed;
	width: 100%;
	padding: 15px 0;
	font-family: 'Montserrat', sans-serif;
	background: tomato;
	z-index: 1;
}
.navbar .sticky{
	padding: 15px;
	background: tomato;

}
.navbar .max-width{
	display: flex;
	align-items: center;
	justify-content: space-between;
}
.navbar .logo a{
	color: white;
	font-size: 35px;
	font-weight: 600;
}
.navbar .logo a:hover{
	color: green;
}
.navbar .logo a span{
	color: white;
}
.navbar .logo a span:hover{
	color: pink;
}
.navbar .menu li{
	list-style: none;
	display: inline-block;
}
.navbar .menu li a{
	display: block;
	color: white;
	font-size: 20px
	font-weight: 600;
	margin-left: 30px;
	transition: all 0.5s linear;

}
.navbar .menu li a:hover{
	color: red;
}
/*Style for Home Section */
.home{
	display: flex;
	background: url("images/Kish1.jpg") repeat center;
	height: 100vh;
	color: red;
	min-height: 500px;
	max-height: 720px;
	background-size: cover;
	background-attachment: fixed;
	font-family: 'Montserrat', sans-serif;
}
.home .max-width{
	margin: auto 0 auto 30px; 
}
.home .home-content .text-1{
	font-size: 25px;
}
.home .home-content .text-2{
	font-size: 50px;
	font-weight: 700;
	margin-left: -3px;
}
.home .home-content .text-3{
	font-size: 25px;
}
.home .home-content a{
	display: inline-block;
	background: red;
	color: white;
	font-size: 20px;
	padding: 12px 36px;
	margin-top: 30px;
	border-radius: 20px;
	transition: all 0.5s linear;

}
.home .home-content a:hover{
	color: white;
	background: turquoise;
}

/*Style for About Section */

section{
	padding: 100px 0;
}
.about{
	display: flex;
	background: url("images/kish3.jpg") repeat center;
	background-size: cover;
	background-attachment: scroll;
	font-family: 'Montserrat', sans-serif;

}
.about .title{
	text-align: center;
	font-size: 30px;
	padding-bottom: 50px;
}
.about .about-content{
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: space-between;
}
.about .about-content .left{
	width: 45%;
}
.about .about-content .left img{
	height: 300px;
	width: 300px;
	object-fit: cover;
	border-radius: 20px;
}
.about .about-content .right{
	width: 55%;
}
.about .about-content .right .text{
	margin-bottom: 20px;
}	
.about .about-content .right p{
	font-size: 20px;
	text-align: justify;
}
/*Style for About Section */
.services{
	color: black;
	background: red;
}
.services .title{
	font-family: 'Montserrat', sans-serif;
	color: white;
	text-align: center;
	font-size: 30px;
	padding-bottom: 50px;
}
.services .services-content{
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: space-between;
}
.services .services-content .card{
	width: calc(33% - 20px);
	background: white;
	text-align: center;
	border-radius: 6px;
	padding: 20px 25px;
}
.services .services-content .card:hover{
	background: aqua;
}
.services .services-content .card .box{
	transition: all 0.3s ease;
}
.services .services-content .card .box:hover{
	transform: scale(1.05); 
}
.services .services-content .card img{
	height: 60px;
	width: 60px;
}
.services .services-content .text{
	font-family: 'Montserrat', sans-serif;
	font-size: 25px;
	font-weight: 600;
	margin: 10px 0;	

}
.services .services-content p{
	font-family: 'Montserrat', sans-serif;
	font-size: 18px;
}

/*Style for About Section */
.skills{
	background: url("images/kish2.jpg") repeat center;
	background-size: cover;
	background-attachment: scroll;
	font-family: 'Montserrat', sans-serif;
	font-size: 18px;
}
.skills .title{
	text-align: center;
	font-size: 30px;
	padding-bottom: 50px;
}
.skills .skills-content{
	display: flex;
	flex-wrap: wrap;
	align-items: center;
	justify-content: space-between;
}
.skills .skills-content .column{
	width: calc(50% - 30px);
}
.skills .skills-content  .left .text{
	font-size: 20px;
	font-weight: 600;
	margin-bottom: 20px;
}
.skills .skills-content  .left p{
	text-align: justify;
	font-size: 18px;
}
.skills .skills-content .left a{
	display: inline-block;
	background: red;
	color: white;
	font-size: 20px;
	padding: 12px 36px;
	margin-top: 30px;
	border-radius: 20px;
	
}
.skills .skills-content .left a:hover{
	color: white;
	background: turquoise;
}
.skills .skills-content .right .bar{
	margin-bottom: 15px;
}
.skills .skills-content .right .info{
	display: flex;
	margin-bottom: 5px;
	align-items: center;
	justify-content: space-between;
}
.skills .skills-content .right .info:hover{
	color: red;
}
.skills .skills-content .right span{
	font-weight: 600;
	font-size: 18px;
	padding: 5px;
}
.skills .skills-content .right .line{
	height: 10px;
	width: 100%;
	background: lightgray;
	position: relative;

}
.skills .skills-content .right .line::before{
	content: "";
	position: absolute;
	height: 100%;
	left: 0;
	right: 0;
