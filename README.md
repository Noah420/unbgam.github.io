
<!DOCTYPE html>
<html lang="en">
<head>
<meta name="theme-color" content="#E77E7E">
<meta property="og:type" content="website" />
<meta property="og:see_also" content="https://ubg100.github.io/" />
<meta property="og:locale" content="en_US" />
<meta name="twitter:card" content="summary" />
<link rel="canonical" href="https://ubg100.github.io/slope" />
<meta property="og:url" content="https://ubg100.github.io/slope" />
<meta property="og:title" content="Slope" />	<meta name="twitter:title" content="Slope" />
<meta property="og:description" content="Play all your favorite games unblocked now!" />
<meta name="twitter:description" content="Play all your favorite games unblocked now!" />
<meta property="og:image" content="https://ubg100.github.io/ubg100.png">
<script data-ad-client="ca-pub-5287266392597979" async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
<meta charset="UTF-8">
<link rel="shortcut icon" type="image/x-icon" href="ubg100.png"/>
<link rel="mask-icon" type="" href="ubg100.png" color="#111"/>
<title>Slope</title>
<link rel='stylesheet' href='https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/4.1.3/css/bootstrap.min.css'>
<link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=UA-159383230-1"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'UA-159383230-1');
</script>
<style>
@import url('https://fonts.googleapis.com/css?family=Montserrat:100,100i,200,200i,300,300i,400,400i,500,500i,600,600i,700,700i,800,800i,900,900i');

body{
	font-family: 'Montserrat', sans-serif;
	font-weight: 300;
	font-size: 15px;
	line-height: 1.7;
	color: #c4c3ca;
	background-color: #1f2029;
	overflow-x: hidden;
	-webkit-transition: all 300ms linear;
	transition: all 300ms linear;
}
a {
	cursor: pointer;
}
a:hover {
	text-decoration: none;
}

/* #Cursor
================================================== */

.cursor,
.cursor2,
.cursor3{
	position: fixed;
	border-radius: 50%;	
	transform: translateX(-50%) translateY(-50%);
	pointer-events: none;
	left: -100px;
	top: 50%;
	mix-blend-mode: difference;
	-webkit-transition: all 300ms linear;
	transition: all 300ms linear;
}
.cursor{
	background-color: #fff;
	height: 0;
	width: 0;
	z-index: 99999;
}
.cursor2,.cursor3{
	height: 36px;
	width: 36px;
	z-index:99998;
	-webkit-transition:all 0.3s ease-out;
	transition:all 0.3s ease-out
}
.cursor2.hover,
.cursor3.hover{
	-webkit-transform:scale(2) translateX(-25%) translateY(-25%);
	transform:scale(2) translateX(-25%) translateY(-25%);
	border:none
}
.cursor2{
	border: 2px solid #fff;
	box-shadow: 0 0 22px rgba(255, 255, 255, 0.6);
}
.cursor2.hover{
	background: rgba(255,255,255,1);
	box-shadow: 0 0 12px rgba(255, 255, 255, 0.2);
}

@media screen and (max-width: 1200px){
	.cursor,.cursor2,.cursor3{
		display: none
	}
}

/* #Primary style
================================================== */

.section {
    position: relative;
	width: 100%;
	display: block;
}
.over-hide{
	overflow: hidden;
}
.full-height {
	height: 100vh;
}

/* #Navigation
================================================== */
 
.cd-header{
    position: fixed;
	width:100%;
	top:0;
	left:0;
	z-index:100;
} 
.header-wrapper{
    position: relative;
	width: calc(100% - 100px);
	margin-left: 50px;
} 
.logo-wrap {
	position: absolute;
	display:block;
	left: 0%;
	top: 25px;
	cursor: pointer;
}
.logo-wrap a {
	cursor: pointer;
	font-family: 'Montserrat', sans-serif;
	font-weight: 900;
	font-size: 20px;
	line-height: 20px;
	text-transform: uppercase;
	letter-spacing: 2px;
	color: #fff;
	transition : all 0.3s ease-out;
}
.logo-wrap a span{ 
	color: #E77E7E;
}
.logo-wrap a:hover {
	opacity: 0.9;
}
.nav-but-wrap{ 
	position: relative;
	display: inline-block;
	float: right;
	padding-left: 15px;
	padding-top: 15px;
	margin-top: 26px;
	transition : all 0.3s ease-out;
}
.menu-icon {
	height: 30px;
	width: 30px;
	position: relative;
	z-index: 2;
	cursor: pointer;
	display: block;
}
.menu-icon__line {
	height: 2px;
	width: 30px;
	display: block;
	background-color: #fff;
	margin-bottom: 7px;
	cursor: pointer;
	-webkit-transition: background-color .5s ease, -webkit-transform .2s ease;
	transition: background-color .5s ease, -webkit-transform .2s ease;
	transition: transform .2s ease, background-color .5s ease;
	transition: transform .2s ease, background-color .5s ease, -webkit-transform .2s ease;
}
.menu-icon__line-left {
	width: 16.5px;
	-webkit-transition: all 200ms linear;
	transition: all 200ms linear;
}
.menu-icon__line-right {
	width: 16.5px;
	float: right;
	-webkit-transition: all 200ms linear;
	-moz-transition: all 200ms linear;
	-o-transition: all 200ms linear;
	-ms-transition: all 200ms linear;
	transition: all 200ms linear;
}
.menu-icon:hover .menu-icon__line-left,
.menu-icon:hover .menu-icon__line-right {
	width: 30px;
}
.nav {
	position: fixed;
	z-index: 98;
}
.nav:before, .nav:after {
	content: "";
	position: fixed;
	width: 100vw;
	height: 100vh;
	background: rgba(20, 21, 26,0.6);
	border-bottom-left-radius: 200%;
	z-index: -1;
	-webkit-transition: -webkit-transform cubic-bezier(0.77, 0, 0.175, 1) 0.6s, border-radius linear 0.8s;
	transition: -webkit-transform cubic-bezier(0.77, 0, 0.175, 1) 0.6s, border-radius linear 0.8s;
	transition: transform cubic-bezier(0.77, 0, 0.175, 1) 0.6s, border-radius linear 0.8s;
	transition: transform cubic-bezier(0.77, 0, 0.175, 1) 0.6s, -webkit-transform cubic-bezier(0.77, 0, 0.175, 1) 0.6s, border-radius linear 0.8s;
	-webkit-transform: translateX(100%) translateY(-100%);
          transform: translateX(100%) translateY(-100%);
}
.nav:after {
	background: rgba(9,9,12,1);
	-webkit-transition-delay: 0s;
          transition-delay: 0s;
}
.nav:before {
	-webkit-transition-delay: .2s;
          transition-delay: .2s;
}
.nav__content {
	position: fixed;
	visibility: hidden;
	top: 50%;
	margin-top: 20px;
	-webkit-transform: translate(0%, -50%);
          transform: translate(0%, -50%);
	width: 100%;
	text-align: center;
}
.nav__list {
	position: relative;
	padding: 0;
	margin: 0;
	z-index: 2;
}
.nav__list-item {
	position: relative;
	display: block;
	-webkit-transition-delay: 0.8s;
          transition-delay: 0.8s;
	opacity: 0;
	text-align: center;
	color: #fff;
	overflow: hidden; 
	font-family: 'Montserrat', sans-serif;
	font-size: 8vh;
	font-weight: 900;
	line-height: 1.15;
	letter-spacing: 3px;
	-webkit-transform: translate(100px, 0%);
          transform: translate(100px, 0%);
	-webkit-transition: opacity .2s ease, -webkit-transform .3s ease;
	transition: opacity .2s ease, -webkit-transform .3s ease;
	transition: opacity .2s ease, transform .3s ease;
	transition: opacity .2s ease, transform .3s ease, -webkit-transform .3s ease;
	margin-top: 0;
	margin-bottom: 0;
}
.nav__list-item a{ 
	position: relative;
	text-decoration: none;
	color: rgba(255,255,255,0.6);
	overflow: hidden; 
	cursor: pointer;
	padding-left: 5px;
	padding-right: 5px;
	font-weight: 900;
	z-index: 2;
	display: inline-block;
	text-transform: uppercase;
    -webkit-transition: all 200ms linear;
    transition: all 200ms linear; 
}
.nav__list-item a:after{ 
	position: absolute;
	content: '';
	top: 50%;
	margin-top: -2px;
	left: 50%;
	width: 0;
	height: 0;
	opacity: 0;
	background-color: #E77E7E;
	z-index: 1;
    -webkit-transition: all 200ms linear;
    transition: all 200ms linear; 
}
.nav__list-item a:hover:after{ 
	height: 4px;
	opacity: 1;
	left: 0;
	width: 100%;
}
.nav__list-item a:hover{
	color: rgba(255,255,255,1);
}
.nav__list-item.active-nav a{
	color: rgba(255,255,255,1);
}
.nav__list-item.active-nav a:after{ 
	height: 4px;
	opacity: 1;
	left: 0;
	width: 100%;
}
body.nav-active .nav__content {
	visibility: visible;
}
body.nav-active .menu-icon__line {
	background-color: #fff;
	-webkit-transform: translate(0px, 0px) rotate(-45deg);
          transform: translate(0px, 0px) rotate(-45deg);
}
body.nav-active .menu-icon__line-left {
	width: 15px;
	-webkit-transform: translate(2px, 4px) rotate(45deg);
          transform: translate(2px, 4px) rotate(45deg);
}
body.nav-active .menu-icon__line-right {
	width: 15px;
	float: right;
	-webkit-transform: translate(-3px, -3.5px) rotate(45deg);
          transform: translate(-3px, -3.5px) rotate(45deg);
}
body.nav-active .menu-icon:hover .menu-icon__line-left,
body.nav-active .menu-icon:hover .menu-icon__line-right {
	width: 15px;
}
body.nav-active .nav {
	visibility: visible;
}
body.nav-active .nav:before, body.nav-active .nav:after {
	-webkit-transform: translateX(0%) translateY(0%);
          transform: translateX(0%) translateY(0%);
	border-radius: 0;
}
body.nav-active .nav:after {
	-webkit-transition-delay: .1s;
          transition-delay: .1s;
}
body.nav-active .nav:before {
	-webkit-transition-delay: 0s;
          transition-delay: 0s;
}
body.nav-active .nav__list-item {
	opacity: 1;
	-webkit-transform: translateX(0%);
          transform: translateX(0%);
	-webkit-transition: opacity .3s ease, color .3s ease, -webkit-transform .3s ease;
	transition: opacity .3s ease, color .3s ease, -webkit-transform .3s ease;
	transition: opacity .3s ease, transform .3s ease, color .3s ease;
	transition: opacity .3s ease, transform .3s ease, color .3s ease, -webkit-transform .3s ease;
}
body.nav-active .nav__list-item:nth-child(0) {
	-webkit-transition-delay: 0.7s;
          transition-delay: 0.7s;
}
body.nav-active .nav__list-item:nth-child(1) {
	-webkit-transition-delay: 0.8s;
          transition-delay: 0.8s;
}
body.nav-active .nav__list-item:nth-child(2) {
	-webkit-transition-delay: 0.9s;
          transition-delay: 0.9s;
}
body.nav-active .nav__list-item:nth-child(3) {
	-webkit-transition-delay: 1s;
          transition-delay: 1s;
}
body.nav-active .nav__list-item:nth-child(4) {
	-webkit-transition-delay: 1.1s;
          transition-delay: 1.1s;
}
body.nav-active .nav__list-item:nth-child(5) {
	-webkit-transition-delay: 1.2s;
          transition-delay: 1.2s;
}
body.nav-active .nav__list-item:nth-child(6) {
	-webkit-transition-delay: 1.3s;
          transition-delay: 1.3s;
}
body.nav-active .nav__list-item:nth-child(7) {
	-webkit-transition-delay: 1.4s;
          transition-delay: 1.4s;
}
body.nav-active .nav__list-item:nth-child(8) {
	-webkit-transition-delay: 1.5s;
          transition-delay: 1.5s;
}
body.nav-active .nav__list-item:nth-child(9) {
	-webkit-transition-delay: 1.6s;
          transition-delay: 1.6s;
}
body.nav-active .nav__list-item:nth-child(10) {
	-webkit-transition-delay: 1.7s;
          transition-delay: 1.7s;
}
.test {
  height: 1000px;
}
.content {
    position: relative;
	margin: auto;
	width: 800px;
	display: block;
	overflow: hidden;
	height: 560px;
	border-radius: 25px;
  	border: 5px solid #E77E7E;
	top: 100px;
}
/* #back to top stuff
================================================== */

@import url('https://fonts.googleapis.com/css?family=Muli:200,200i,300,300i,400,400i,600,600i,700,700i,800,800i,900,900i&subset=latin-ext,vietnamese');


:root {
	font-size: 20px;
	--red: #da2c4d;
	--yellow: #f8ab37;
	--green: #2ecc71;
	--white: #ffffff;
	--grey-light: #f2f7f9;
	--grey: #ecedf3;
	--black: #080808;
	--black-blue: #1f2029;
	--black-blue-light: #353746;
	--black-blue-light-2: #404255;
	--black-blue-light-3: #4b4d64;
	--black-light: #424455;
  --ubg: #E77E7E;
}
body{
    font-family: 'Raleway', sans-serif;
	font-size: 16px;
	font-weight: 500;
	line-height: 1.65;
	color: var(--grey);
	background-color: var(--black-blue);
	overflow-x: hidden;
	letter-spacing: 0.2px;
	-webkit-transition: all 200ms linear;
	transition: all 200ms linear; 
	text-rendering: optimizeLegibility !important;
	-webkit-font-smoothing: antialiased !important;
}

.section {
    position: relative;
	width: 100%;
	display: block;
	overflow: hidden;
	height: 100vh;
}

/* #Progress wrap starts here
================================================== */

.progress-wrap {
	position: fixed;
	right: 50px;
	bottom: 50px;
	height: 46px;
	width: 46px;
	cursor: pointer;
	display: block;
	border-radius: 50px;
	box-shadow: inset  0 0 0 2px rgba(255,255,255,0.2);
	z-index: 97;
	opacity: 0;
	visibility: hidden;
	transform: translateY(15px);
	-webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
.progress-wrap.active-progress {
	opacity: 1;
	visibility: visible;
	transform: translateY(0);
}
.progress-wrap::after {
	position: absolute;
	font-family: 'unicons';
	content: '\e84b';
	text-align: center;
	line-height: 46px;
	font-size: 24px;
	color: var(--ubg);
	left: 0;
	top: 0;
	height: 46px;
	width: 46px;
	cursor: pointer;
	display: block;
	z-index: 1;
	-webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
.progress-wrap:hover::after {
	opacity: 0;
}
.progress-wrap::before {
	position: absolute;
	font-family: 'unicons';
	content: '\e84b';
	text-align: center;
	line-height: 46px;
	font-size: 24px;
	opacity: 0;
	background-image: linear-gradient(298deg, var(--red), var(--yellow));
	-webkit-background-clip: text;
	-webkit-text-fill-color: transparent;
	left: 0;
	top: 0;
	height: 46px;
	width: 46px;
	cursor: pointer;
	display: block;
	z-index: 2;
	-webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
.progress-wrap:hover::before {
	opacity: 1;
}
.progress-wrap svg path { 
	fill: none; 
}
.progress-wrap svg.progress-circle path {
	stroke: var(--ubg);
	stroke-width: 4;
	box-sizing:border-box;
	-webkit-transition: all 200ms linear;
    transition: all 200ms linear;
}
.myButton {
	background-color:#E77E7E;
	border-radius:10px;
	display: inline-block;
	cursor: pointer;
	color:#fff;
    font-family: Montserrat, sans-serif;
	font-size: 17px;
    font-weight: 400;
	padding: 16px 16px;
	text-decoration: none;
	margin-top: 110px;
}
.myButton:hover {
	background-color:#A25858;
    transition: all 0.3s ease 0s;
	box-shadow: 3px 3px 3px rgba(0, 0, 0, 0.3);
}
.myButton:active {
	position:relative;
	top:1px;
}
.fsbutton {
	text-align: center;
	margin-right: 645px;
}
.titletext{
	font-family: Montserrat, sans-serif;
    margin-right: 500px;
    display: flex;
    justify-content: center;
    align-content: center;
}
i.material-icons {
  font-size: 50px;
  vertical-align: middle;
  position: relative;
  top: -2px;
  color: white;
}
* {
  margin: 0;
  padding: 0;
  -moz-box-sizing: border-box;
  -webkit-box-sizing: border-box;
  box-sizing: border-box;
}

.tabs {
  width: 650px;
  float: none;
  list-style: none;
  position: relative;
  margin: 80px 0 200px 10px;
  text-align: left;
}
.tabs li {
  float: left;
  display: block;
}
.tabs input[type="radio"] {
  position: absolute;
  top: 0;
  left: -9999px;
}
.tabs label {
  display: block;
  padding: 14px 21px;
  border-radius: 15px 15px 0 0;
  font-size: 20px;
  font-weight: normal;
  text-transform: uppercase;
  background: #E77E7E;
  cursor: pointer;
  position: relative;
  top: 4px;
  -moz-transition: all 0.2s ease-in-out;
  -o-transition: all 0.2s ease-in-out;
  -webkit-transition: all 0.2s ease-in-out;
  transition: all 0.2s ease-in-out;
}
.tabs label:hover {
  background: #A25858;
}
.tabs .tab-content {
  z-index: 2;
  display: none;
  overflow: hidden;
  width: 1140px;
  font-size: 17px;
  line-height: 25px;
  padding: 25px;
  position: absolute;
  top: 53px;
  left: 0;
  background: #A25858;
}
.tabs [id^="tab"]:checked + label {
  top: 0;
  padding-top: 17px;
  background: #A25858;
}
.tabs [id^="tab"]:checked ~ [id^="tab-content"] {
  display: block;
}
i.tabz {
  font-size: 30px;
  vertical-align: middle;
  position: relative;
  top: -2.5px;
  right: 5px;
  color: white;
}
p.desc{
    font-size: 20px;
    line-height: 2;
}
</style>
<script>
  window.console = window.console || function(t) {};
</script>
<script>
  if (document.location.search.match(/type=embed/gi)) {
    window.parent.postMessage("resize", "*");
  }
</script>
</head>
<body translate="no" id="ancss">
<link rel='stylesheet' href='https://s3-us-west-2.amazonaws.com/s.cdpn.io/1462889/unicons.css'>
<header class="cd-header">
<div class="header-wrapper">
<div class="logo-wrap">
<a href="https://ubg100.github.io/" class="hover-target"><span>UBG</span>100</a>
<a href="https://ubg100.github.io/" class="hover-target"><img id="myImage" src="ubg100.png"></a>
</div>
<div class="nav-but-wrap">
<div class="menu-icon hover-target">
<span class="menu-icon__line menu-icon__line-left"></span>
<span class="menu-icon__line"></span>
<span class="menu-icon__line menu-icon__line-right"></span>
</div>
</div>
</div>
</header>
<div class="nav">
<div class="nav__content">
<ul class="nav__list">
<li class="nav__list-item"><a href="https://ubg100.github.io/" class="hover-target">home</a></li>
<li class="nav__list-item"><a href="https://ubg100.github.io/games-list" class="hover-target">games list</a></li>
<li class="nav__list-item"><a href="https://ubg100.github.io/faq" class="hover-target">faq</a></li>
<li class="nav__list-item"><a href="#" class="hover-target"></a></li>
</ul>
</div>
</div>
	<div class="progress-wrap">
<svg class="progress-circle svg-content" width="100%" height="100%" viewBox="-1 -1 102 102">
<path d="M50,1 a49,49 0 0,1 0,98 a49,49 0 0,1 0,-98" />
</svg>
</div>
	<div class="test">
<section class="content">
	<div><div id="971542060501934713" align="left" style="width: 100%; overflow-y: hidden;" class="wcustomhtml"><div id="674164033572568842" align="inherit" style="width: 100%; overflow-y: hidden;" class="wcustomhtml"><div><div id="370896482962142208" align="left" style="width: 100%; overflow-y: hidden;" class="wcustomhtml"><div><div id="673953926798312800" align="center" style="width: 100%; overflow-y: hidden;" class="wcustomhtml">
    <meta charset="utf-8">
    <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
    <link rel="stylesheet" href="style.css">
    <script src="UnityProgress.js"></script>
    <script src="unityloader41.js"></script>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>
    <script src="webglads.js" type="text/javascript"></script>
    <script>
      var gameInstance = UnityLoader.instantiate("gameContainer", "slope_new.json", {onProgress: UnityProgress,Module:{onRuntimeInitialized: function() {UnityProgress(gameInstance, "complete")}}});
    </script>
    <div class="webgl-content">
        <div id="gameContainer" style="width: 800px; height: 560px; margin: 0px; padding: 0px; border: 0px; position: relative; background: rgb(35, 31, 32);"><canvas id="#canvas" style="cursor: default;" width="800" height="560"></canvas><div class="logo Dark" style="display: none;"></div><div class="progress Dark" style="display: none;"><div class="empty" style="width: 0%;"></div><div class="full" style="width: 100%;"></div></div></div>
        <div class="footer">
            <div class="webgl-logo"></div>
            <div class="fullscreen" onclick="gameInstance.SetFullscreen(1)"></div>
        </div>
    </div>
</div>
</div>



</div>
			</div>
		</div>
      </div>

	</div>
	  </section>
	  <div class = "fsbutton">
		<a class="myButton" onclick="goFullscreen()"><i class="material-icons tabz">crop_free</i>Fullscreen</a>
	  <script>
		  var elem = document.getElementById("gameContainer");
		  function goFullscreen() {
		  if (elem.requestFullscreen) {
		  elem.requestFullscreen();
		  } else if (elem.mozRequestFullScreen) {
		  elem.mozRequestFullScreen();
		  } else if (elem.webkitRequestFullscreen) {
		  elem.webkitRequestFullscreen();
		  } else if (elem.msRequestFullscreen) {
		  elem.msRequestFullscreen();
		  }
		  }
	  </script></div>
	  <div class="titletext">
		  <ul class="tabs" role="tablist">
		  <li>
			  <input type="radio" name="tabs" id="tab1" checked />
			  <label for="tab1" role="tab" aria-selected="true" aria-controls="panel1" tabindex="0"><i class="material-icons tabz">article</i>Description</label>
			  <div id="tab-content1" class="tab-content" role="tabpanel" aria-labelledby="description" aria-hidden="false">
			  <p class="desc">Slope is the ultimate running game that will put your skills to the test. Speed down on a randomized slope. The farther you go, the faster your ball travels. This game might look simple but playing this will give you extreme adrenaline rush. Just remember to avoid obstacles and those red blocks. Always be on track to get a high score and you might have your name on the leaderboard!</p>
			  </div>
		  </li>
		  <li>
			  <input type="radio" name="tabs" id="tab2" />
			  <label for="tab2" role="tab" aria-selected="false" aria-controls="panel2" tabindex="0"><i class="material-icons tabz">keyboard</i>Controls</label>
			  <div id="tab-content2" class="tab-content" role="tabpanel" aria-labelledby="specification" aria-hidden="true">
			  <p class="desc">AD/QD/Arrow Keys: Control movement</p>
			  </div>
		  </li>
		  <li>
			  <input type="radio" name="tabs" id="tab3" />
			  <label for="tab3" role="tab" aria-selected="false" aria-controls="panel3" tabindex="0"><i class="material-icons tabz">verified</i>Developer</label>
			  <div id="tab-content3" class="tab-content" role="tabpanel" aria-labelledby="specification" aria-hidden="true">
			  <p class="desc">This game was created by Rob Kay!</p>
			  </div>
		  </li>
		  </ul>
	  </div>
	  <div class="test">
        <br>
        <br>
        <br>
        <br>
        <br>
      <div align="center"><script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script>
      <!-- Horizontal Ads -->
      <ins class="adsbygoogle"
         style="display:block"
         data-ad-client="ca-pub-5287266392597979"
         data-ad-slot="1416948905"
         data-ad-format="auto"
         data-full-width-responsive="true"></ins>
      <script>
         (adsbygoogle = window.adsbygoogle || []).push({});
      </script></div></div>
<script src="https://static.codepen.io/assets/common/stopExecutionOnTimeout-9bf952ccbbd13c245169a0a1190323a27ce073a3d304b8c0fdf421ab22794a58.js"></script>	
<script src='https://cdnjs.cloudflare.com/ajax/libs/jquery/3.3.1/jquery.min.js'></script>
<script id="rendered-js">
(function ($) {"use strict";

  //Navigation

  var app = function () {
    var body = undefined;
    var menu = undefined;
    var menuItems = undefined;
    var init = function init() {
      body = document.querySelector('body');
      menu = document.querySelector('.menu-icon');
      menuItems = document.querySelectorAll('.nav__list-item');
      applyListeners();
    };
    var applyListeners = function applyListeners() {
      menu.addEventListener('click', function () {
        return toggleClass(body, 'nav-active');
      });
    };
    var toggleClass = function toggleClass(element, stringClass) {
      if (element.classList.contains(stringClass)) element.classList.remove(stringClass);else element.classList.add(stringClass);
    };
    init();
  }();


  //Switch light/dark actual

  $("#switch").on('click', function () {
    if ($("body").hasClass("light")) {
      $("body").removeClass("light");
      $("#switch").removeClass("switched");
    } else
    {
      $("body").addClass("light");
      $("#switch").addClass("switched");
    }
  });

})(jQuery);


/* Please ❤ this if you like it! */



(function ($) {"use strict";

  //Switch dark/light

  $(".switch").on('click', function () {
    if ($("body").hasClass("light")) {
      $("body").removeClass("light");
      $(".switch").removeClass("switched");
    } else
    {
      $("body").addClass("light");
      $(".switch").addClass("switched");
    }
  });

  $(document).ready(function () {"use strict";

    //Scroll back to top

    var progressPath = document.querySelector('.progress-wrap path');
    var pathLength = progressPath.getTotalLength();
    progressPath.style.transition = progressPath.style.WebkitTransition = 'none';
    progressPath.style.strokeDasharray = pathLength + ' ' + pathLength;
    progressPath.style.strokeDashoffset = pathLength;
    progressPath.getBoundingClientRect();
    progressPath.style.transition = progressPath.style.WebkitTransition = 'stroke-dashoffset 10ms linear';
    var updateProgress = function () {
      var scroll = $(window).scrollTop();
      var height = $(document).height() - $(window).height();
      console.log($(document).height());
      console.log($(window).height());
      var progress = pathLength - scroll * pathLength / height;
      progressPath.style.strokeDashoffset = progress;
    };
    updateProgress();
    $(window).scroll(updateProgress);
    var offset = 50;
    var duration = 550;
    jQuery(window).on('scroll', function () {
      if (jQuery(this).scrollTop() > offset) {
        jQuery('.progress-wrap').addClass('active-progress');
      } else {
        jQuery('.progress-wrap').removeClass('active-progress');
      }
    });
    jQuery('.progress-wrap').on('click', function (event) {
      event.preventDefault();
      jQuery('html, body').animate({ scrollTop: 0 }, duration);
      return false;
    });


  });

})(jQuery);
//# sourceURL=pen.js
	</script>
	<script>
		(function() {
		  var externallyFramed = false;
		  try {
			externallyFramed = top.location.host != location.host;
		  }
		  catch(err) {
			externallyFramed = true;
		  }
		  if(externallyFramed) {
			var ancss = document.getElementById("ancss");
			ancss.parentNode.removeChild(ancss);
		  }
		})();
	  </script>
	
</body>
</html>
