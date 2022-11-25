# Einbinden von Grafiken

		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Einbinden von Grafiken</title>
			</head>
			<body>
				<h1>Einbinden von Grafiken</h1>
			</body>

			<img src="C:\Users\User\.vscode\HTML\2022-11-14\images\portrait-2.jpg"alt="EinTyp">
			<p>Bildunterschrift</p>
			<!-- original größe -->

			<img src="C:\Users\User\.vscode\HTML\2022-11-14\images\AUSTRIA-a.jpg"alt="EinTyp" width="450" height="450">
			<p>Bildunterschrift</p>

			<!-- benutzerdefinierte höhe/breite-->
			
			<img src="C:\Users\User\.vscode\HTML\2022-11-14\images\AUSTRIA-a.jpg"alt="EinTyp" width="100">
			<p>Bildunterschrift</p>

			<img src="C:\Users\User\.vscode\HTML\2022-11-14\images\AUSTRIA-a.jpg"alt="EinTyp" width="30%">
			<p>Bildunterschrift</p>

			 <!-- Auflösung Pixel oder Prozent -->
		  
			 <figure>
				<img src="C:\Users\User\.vscode\HTML\2022-11-14\images\erde.jpg"alt="EinTyp" width="30%">
		   <figcaption>Bildunterschrift</figcaption>
			 </figure>
			 <!-- Semantischer Zusammenhang zwischen Bild und Bildbeschreibung-->

			 <img src="https://th.bing.com/th/id/R.341fba5c15ea53a0f626405ea3fa2380?rik=sNU%2f6rXI9wmw5A&riu=http%3a%2f%2fwww.plantenkontor.de%2fWebRoot%2fStore14%2fShops%2f80759616%2f58A5%2f63B4%2f0044%2fB9B2%2f19D0%2fC0A8%2f2AB8%2fF955%2franunculus-_rosa.jpg&ehk=4Ijqc5zImL3ZK17votEmW1pSZw15kc3serSZ7J%2b3f8o%3d&risl=&pid=ImgRaw&r=0"alt="Ranunkeln" width="450" height="350">

				<!-- bilder in anhängigkeit von der bilschirmauflösung laden-->

				<!-- <figure>
					<img src="C:\Users\User\.vscode\HTML\2022-11-14\images\small.jpg"alt="EinTyp" 
					srcset="C:\Users\User\.vscode\HTML\2022-11-14\images\small.jpg 1x, C:\Users\User\.vscode\HTML\2022-11-14\images\medium.jpg 2x, C:\Users\User\.vscode\HTML\2022-11-14\images\large.jpg 3x">
			
				 </figure> -->

				 <picture>
					<source media="(min-width: 6400px)" src="C:\Users\User\.vscode\HTML\2022-11-14\images\medium.jpg">
					<source src="C:\Users\User\.vscode\HTML\2022-11-14\images\small.jpg">
				 </picture>
		</html>
