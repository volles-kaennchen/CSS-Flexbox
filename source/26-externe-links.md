# Externe Hyperlinks mit Icon kennzeichnen


				<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Externe Hyperlinks mit Icon kennzeichnen</title>
			<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/simple-line-icons/2.5.5/css/simple-line-icons.min.css">

				<style>
					body{
					font-family: sans-serif;
					}

					/* Variante 1: selektiere das target-Attribut */

					/* a[target]::after{
						font-family: 'Simple-Line-Icons';
						content: " \e05a";} */
					
					a[href^="https://"]::after{
					font-family: 'Simple-Line Icons';
					content: " \260D";}
				</style>

			</head>
			<body>
				<h1>Externe Hyperlinks mit Icon kennzeichnen</h1>

				<p><a href="https://google.de">Google</a></p>
				<p><a href="../2022-11-17/uebung/website-newsletter/newsletter-hotel-vallora.html">Newsletter Hotel Vallora</a></p>
				<p><a href="https://www.iad.de" target="_blank">IAD GmbH</a></p>
			</body>
		</html>
