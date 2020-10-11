# hello-world

Hola! Que tal?
Soy Victor Colina.

<!DOCTYPE html>
<html>
<head>
	<title>The Postcard</title>
	<link rel="stylesheet" type="text/css" href="style.css">
	<link href="https://fonts.googleapis.com/css2?family=Handlee&display=swap" rel="stylesheet">
</head>
<body>
	<div class="contenido">
		<header>
		
		</header>

		<section>
			<form class="postcard" action="https://formspree.io/info@breatheco.de" method="post">
				<div class="header-postcard">
					<img src="http://assets.breatheco.de/apis/img/icon/4geeks.png">
					<h1>My Postcard</h1>
				</div>
					<div class="body-postcard">
						<div class="left-part">
				<p>Look how awesome! This is a postcard that I created using HTML5 and CSS3 during my 4geeks Academy course!</p> 
				<p>This is so cool, can´t wait to start doing more stuff!</p>
						</div>

					<div class="right-part">
						<input type="text" name="fullname" placeholder="Some name">
						<input type="text" name="email" placeholder="Some email">
						<input type="text" name="message" placeholder="Some comment">
					</div>
				</div>

				<div class="footer-postcard">
					<input type="submit" value="Send My Postcard">
				</div>
			</form>

					
		</section>

		<footer>
		
		</footer>
	</div>
</body>
</html>

body {background: #171717; font-size: 22px;}
input {font-size: 19px; font-family: 'Handlee', cursive; font-weight: bold;}
.header-postcard img {max-width: 60px; float: right;}
.header-postcard {overflow: hidden;}
.body-postcard {overflow: hidden;}
.footer-postcard {padding: 05px; text-align: center;}
.footer-postcard {font-family: 'Handlee', cursive; font-weight: bold;} 
.footer-postcard input [type=submit] {background: #cdcdcd; color: black; border-bottom: 1px; font-family: 'Handlee', cursive; font-weight: bold;}
.postcard {background: white; width: 550px; height: 400px; margin: auto; 
	position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%);
	padding: 16px;}
.left-part {float: left; width: 50%;}
.right-part {float: right; width: 50%;}
.right-part input {display: block;}
.contenido {font-family: 'Handlee', cursive; font-weight: bold;}
