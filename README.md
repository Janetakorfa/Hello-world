# Hello-world
My first github
<!DOCTYPE html>
<html>
<head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>Women in Web</title>
        <meta name="description" content="Women in Web">
        <link rel="stylesheet" href="wib.css">
		<link href="https://fonts.googleapis.com/css?family=Dosis|Lato|Oswald|Pacifico|Roboto" rel="stylesheet">
</head>
<body>
<div class="bg-img">
    <div class="navbar"
		<div class="container">
		<div class="logo_div">
			<img src="img/wib.png" alt="logo of women in web" class="logo">

		<div class="nav_links">
            <ul class="menu">
                <li><a href="#">Home</a></li>
				<li><a href="#">Our Services</a></li>
				<li><a href="#">Our Works</a></li>
				<li><a href="#">About Us</a></li>
				<li><a href="#">Contact Us</a></li>
            </ul>
        </div>  
		</div>
	</div>	
		</div>
<div class="intro">INTRODUCING WOMEN IN WEB</div>
<div class="intro-down">We train and empower females to receive the best offers</div>

<div id="ourservice">
            
                <div id="service"> <p>"We need to understand that if we all work on inclusion together,<br> it’s going to be faster, broader, better,<br> and more thorough than anything we can do on our own."<br>
				-ELLEN PAO</p></div>
                    
            </div>
			<div class="intouch">
  <h1>Join our team</h1>
  <p>Please fill in the details below.</p>
</div>

<form action="" class="mainWrap">
  <input placeholder="Full Name" type="text" class="name" />
  <input placeholder="Email Address" type="email" class="email" />
  <textarea placeholder="Any message?" class="mainArea"></textarea>
  <button class="bigBtn"><i class="fa fa-inbox"></i> Submit</button>
</form>

<footer>
   <div id="footer1">
        <div id="footer-copyright-wrapper"></div>
          <p id="footer-copyright-text">©2020. | Designed By: Yaa W. | All rights reserved.
          </p>
		  </div>
		  </footer>
</body>
*{
	margin: 0;
	padding: 0;
}
.bg-img {
  background-image: url("img/wib9.webp");
  min-height: 700px;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
.container{
	width: 90%;
	margin: 0 auto;
}
.navbar{
	width: 100%;
	overflow: hidden;
	height: 100px;
	line-height: 70px;
	background: white;
}
.logo{
padding: 30px;
float: left;
}
.menu{
	float: right;
}
.menu li{
	float:left;
	width: 120px;
	height: 70px;
	line-height: 70px;
	text-align: left;
	list-style: none;
	padding: 30px;
}
.menu li a{
	color: black;
	text-decoration: none;
	font-family: arial;
	display: block;
}
.menu li a:hover{
	color: pink;
}
.intro {
  position: absolute;
  top: 50%;
  left: 50%;
  color: black;
  transform: translate(-50%, -10%);
  font-size: 90px;
  font-family: Trebuchet MS, Helvetica, sans-serif;
}
.intro-down {
  position: absolute;
  top: 90%;
  left: 50%;
  color: black;
  transform: translate(-50%, -50%);
  font-size: 30px;
  font-family: 'lato';
}
#ourservice{
	height: 250px;
}
#service{
	text-align: center;
	margin: 100px;
	padding: 10px;
	font-family: 'pacifico';
	font-size: 24px;
	background-color: ghostwhite;
}

.intouch {
  max-width:900px;
  width:80%;
  margin:0 auto;
  padding:40px 0px 40px 0px;
  
}

.intouch h1 {
  font-size:50px;
  font-family:"Gentium Book Basic";
  font-weight:900;
  color:black;
  letter-spacing:-3px;
  text-align: center;
}

.intouch p {
  font-family:"Gentium Book Basic";
  font-size:20px;
  color:black;
  letter-spacing:1px;
  text-align: center;
}

.fa {
  margin-right:10px;
}

.mainWrap {
  max-width:900px;
  width:80%;
  margin:0 auto;
  padding-bottom:100px;
}

.name,
.email {
  width:39%;
  border:0;
  background:#fff;
  padding:20px;
  font-size:1.2em;
  font-family:"Gentium Book Basic";
  border-bottom: 2px solid gray;
   color:#111;
}


.name {
  float:left;
}

.email {
  float:right;
}

.mainArea {
 width:100%;
  border:0;
  background:#fff;
  padding:20px;
  font-size:1.2em;
  font-family:"Gentium Book Basic";
  border-bottom: 2px solid gray;
   color:#111; 
}

.bigBtn {
  width:100%;
  padding:20px;
  text-align:center;
  margin-top:20px;
  font-size:25px;
  font-family:"Gentium Book Basic";
  background:black;
  color:white;
  cursor:pointer;
}

@media (max-width: 30em) {
  .intouch h1 {
    font-size:2.3em;
    letter-spacing:0;
  }
  
  .intouch p {
    font-size:1.1em;
    line-height:1.4em;
  }
  
  .name,.email {
    width:100%;
  }
  
  .email {
    margin-top:20px;
  }
  
  .bigBtn {
    font-size:25px;
  }
  

	

