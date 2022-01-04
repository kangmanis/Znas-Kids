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
