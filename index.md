<!DOCTYPE HTML>
<html>
	<head>
		<meta charset="UTF-8">
		<title>SO.CL Social</title>
		<link rel="icon" href="images/icon.ico" type="image/x-icon">
		<link rel="stylesheet" type="text/css" href="style.css">
	
		<link rel="ico" type="image/x-icon" href="image/favicon.ico">
		<link rel="stylesheet" type="text/css" href="slick/slick.css">
		<link rel="stylesheet" type="text/css" href="slick/slick-theme.css">
	</head>
	<body>
		<div id='wallpaper'>
			<h1>So.cl</h1>
		</div>
		<div id='navigator'>
			<img src="images/usericon.png" alt=" " height="20">
			<a href="">Sing in</a>
			<img src="images/group.png" alt=" " height="20">
			<a href="index.html">Social</a>
			<img src="images/contacts.png" alt=" " height="20">
			<a href="contacts.html">Contacts</a>
			<img src="images/messenger.png" alt=" " height="20">
			<a href="messenger.html">Messenger</a>
			<img src="images/outlookmail.png" alt=" " height="20">
			<a href="https://outlook.live.com">Outlook</a>
			<img src="images/msnnews.png" alt=" " height="20">
			<a href="https://www.msn.com">MSN</a>
			<img src="images/office.png" alt=" " height="20">
			<a href="https://home.office.com">Office</a>
			<img src="images/bing.png" alt=" " height="20">
			<a href="https://www.bing.com">Bing</a>
			<img src="images/onedrive.png" alt=" " height="20">
			<a href="https://onedrive.live.com">OneDrive</a>
			<img src="images/info.png" alt=" " height="20">
			<a href="about.html">About So.cl</a>
			<img src="images/games.png" alt=" " height="20">
			<a href="games.html">Games</a>
			<img src="images/xbox.png" alt=" " height="20">
			<a href="https://www.xbox.com">Xbox</a>
			<img src="images/video.png" alt=" " height="20">
			<a href="videos.html">Videos</a>
		</div>
		<div id='social'>
			<img src="images/write.png" alt=" " height="20">
			<a href="writepost.html">Write Post</a>
			<img src="images/createpost.png" alt=" " height="20">
			<a href="createpost.html">Create Post</a>
		</div>
		<h2>Whats new?</h2>

		<div class="your-class">
			<div>
				<img id='slide1' src="">
				<p id='slide1'></p>
			</div>
			<div>
				<img id='slide2' src="">
				<p id='slide2'></p>
			</div>
			<div>
				<img id='slide3' src="">
				<p id='slide3'></p>
			</div>
			<div>
				<img id='slide4' src="">
				<p id='slide4'></p>
			</div>
			<div>
				<img id='slide5' src="">
				<p id='slide5'></p>
			</div>
			<div>
				<img id='slide6' src="">
				<p id='slide6'></p>
			</div>
			<div>
				<img id='slide7' src="">
				<p id='slide7'></p>
			</div>
			<div>
				<img id='slide8' src="">
				<p id='slide8'></p>
			</div>
			<div>
				<img id='slide9' src="">
				<p id='slide9'></p>
			</div>
			<div>
				<img id='slide10' src="">
				<p id='slide10'></p>
			</div>
		</div>

		<script type="text/javascript" src="https://code.jquery.com/jquery-1.11.0.min.js"></script>
		<script type="text/javascript" src="https://code.jquery.com/jquery-migrate-1.2.1.min.js"></script>
		<script type="text/javascript" src="slick/slick.min.js"></script>

		<script type="text/javascript">
			$(document).ready(function () {
				$('.your-class').slick({
					dots: true,
					infinite: true,
					speed: 300,
					slidesToShow: 1,
					adaptiveHeight: true
				});
			});
		</script>
	</body>
</html>
