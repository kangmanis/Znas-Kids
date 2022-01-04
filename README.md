<!DOCTYPE html>
<html>
<meta name="viewport" content="width=device-width, initial-scale=1">
<head>
<title>DonationForm</title>
<img 	class= "logo" style="width:10%" src= "logo.png">


<head>
	<style>
body{
	background-image: url('bg.png');
 	background-repeat: no-repeat;
  	background-attachment: fixed;
  	background-size: cover;

	font-family: Montserrat, "Open Sans", Helvetica, Arial, sans-serif;
	font-weight:800;
	}

.logo {  display: block;
  margin-left: auto;
  margin-right: auto;}

.horizontal {
 	list-style-type: none;
 	margin: 0px;
  	padding: 0;
  	overflow: auto;
  	background-color: #000080;
	display: flex;
	padding: 14px 16px;
	justify-content:space-between;
	}

.block {
	font-size: 0.875em;
  	border: none;
  	outline: none;
  	color: white;
	margin: 0px;
	padding: 10px 16px;
  	background-color: #000080;
  	font-family: Montserrat, "Open Sans", Helvetica, Arial, sans-serif;
	font-weight:800;
	display:block;
	text-decoration: none;
	}

.block:hover:not(.active) {
  	background-color: #bbb;
	border-radius: 5px;
  	}

.active {
  	background-color:white;
	color:#000080;
	border-radius:5px;
  	}

.dropdown .dropbtn {
  	font-size: 0.875em;
  	border: none;
  	outline: none;
  	color: white;
	margin: 0px;
	padding: 10px 16px;
  	background-color: #000080;
  	font-family: Montserrat, "Open Sans", Helvetica, Arial, sans-serif;
	font-weight:800;
	display:block;
	text-decoration: none;
}

.dropdown:hover .dropbtn {
  	background-color: #bbb;
	border-radius: 5px;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f9f9f9;
  min-width: 160px;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  float: none;
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
  text-align: left;
}

.dropdown-content a:hover {
  background-color: #ddd;
}

.dropdown:hover .dropdown-content {
  display: block;
}

.button {
    position: static;
    padding:7px 15px;
    border:2px solid #000080;
    background-color:#000080;
    color:#fafafa;
	  border-radius: 5px;
}

.button:hover  {
    background-color:#bbb;
    color:#000080;
		border-radius: 5px;
}

a{
	text-decoration: none;
}

.row {
  border: 1px solid black;
  margin-top: 10px;
  margin-bottom: 10px;
  margin-left: 27%;
  border-radius: 20px;
  padding-bottom: 65px;
  width: 70%;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
}
/*height: auto;*/
img {
     border-radius: 10%;
}
.row2 {
	border-radius: 20px;
	width: 25%;
  padding-bottom: 5px;
  padding-top: 10px;
}

.row3 {
  text-align: center;
  border: none;
  margin-top: 10px;
  margin-bottom: 4px;
  margin-right: 100px;
}

h2 {
	text-align: center;
	font-family: Montserrat, Open Sans, "Helvetica", Arial, sans-serif;
	font-weight:700;
	color:black;
}

p {
	text-align: center;
	font-family: Montserrat, Open Sans, "Helvetica", Arial, sans-serif;
	font-weight:500;
	font-size: 0.70em;
	margin-right: 100px;
	margin-left: 100px;
}

.p2{
	text-align: right;
	font-weight:100;
	font-size: 0.80em;
}

.main {
	margin-left: 10px;
  margin-right: 10px;
	font-size: 20px;
  padding-bottom: 5px;
  padding-top: 20px;
}

.main1 {
	margin-left: 30px;
  margin-right: 10px;
	font-size: 20px;
  padding-bottom: 5px;
  padding-top: 20px;
}
	</style>
	</head>
	<body>
		<ul class="horizontal">
			<li><button id="index" class= "block" onclick="window.location.href='Index.html'">Home</button></li>
			<li class="dropdown">
				<button class="dropbtn active">Articles
    				</button>
				<div class="dropdown-content">
      					<a href="news.html">News</a>
      					<a href="health.html">Health</a>
      					<a href="activities.html">Activities</a>
    				</div>
			</li>
			<li><button id="class" class= "block active" onclick="window.location.href='Class.html'">Class</button></li>
			<li><button id="donation" class= "block" onclick="window.location.href='Donation.html'">Donation</button></li>
			<li style="float:right"><button id="aboutUs" class= "block" onclick="window.location.href='Aboutus.html'">About Us</button></li>
		</ul>

		<div class="main1">
		<div class="main">
			<a href="ScienceO1.html">
			<img src="Science.png" class="row2" width="300" height="212" style="float:left"/>
			<div class="row"><br>
			<h2 class="row3">Science Class for Preschoolers</h2><hr></a>
			<p>A fun approach of learning Science.
				Children engage in hands-on activities, watch spectacular demonstrations.</p>
			</div></div>

			<div class="main">
				<a href="MusicO1.html">
				<img src="Music.jpg" class="row2" width="300" height="212" style="float:left"/>
				<div class="row"><br>
				<h2 class="row3">Music Class for Middle Childhood</h2><hr></a>
				<p>Our music classes for kids provide a fun,
					comfortable environment for children. Support your child learn new skills
					in an enchanting musical environment.</p>
				</div></div>

				<div class="main">
					<a href="SportO1.html">
					<img src="Sport.jpg" class="row2" width="300" height="212" style="float:left"/>
					<div class="row"><br>
					<h2 class="row3">Sport Class for Middle Childhood</h2><hr></a>
					<p>Make our child healthy and strong. Our professional athletes will teach your child all
						kind of sports. Starts from badminton, football, karate,
						swimming, and so on</p>
					</div></div>

					<div class="main">
						<a href="ArtO1.html">
						<img src="Art.jpg" class="row2" width="300" height="212" style="float:left"/>
						<div class="row"><br>
						<h2 class="row3">Art Class for Preschoolers</h2><hr></a>
						<p>Increase your child's creativity by honing their talents in the art classes we provide.
							Equipped with adequate facilities and a comfortable environment</p>
						</div></div><br>
						<footer></br>
							<i><p class="p2" text-align: right; >Copyright &copy 2021 ZNAS KID  OFFICIAL</p></i>
						</br></footer>
					</div>
	</body>

</html>
