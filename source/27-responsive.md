# Responsive Seiten


				<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Responsive Seiten</title>

			<style>

			body {
				font-family: sans-serif;
			}

			/* === Smartphones, kleine Monitore === */
			h1{
				color: brown;
				font-size: 1.5rem;
			}

			.tablet,
			.desktop {
			display: none;
			}

			/* === Tablets und mittlere Größen ab 426px Breite === */
			@media screen and (min-width: 426px) {
				h1 {color: aquamarine;
				font-size: 2rem;}

				/* Absatz für Tablets */
				.tablet {
				display: block;}
				/* Absatz für Smartphones */
				.smartphones {
				display: none;
				}
			   }

			 /* === Desktops ab 769px Breite === */
			 @media screen and (min-width: 769px) {
				h1 {color: darkgoldenrod;
				font-size: 2rem;}

				/* Absatz für Tablets ausblenden */
				.tablet {
				display: none;}

				/* Absatz für Desktops einblenden */
					.desktop{display: block;}
			   }
				</style>
				</head>
			<body>
				<h1>Responsive Seiten</h1>
				<p class="smartphone">Dieser Absatz ist nur auf dem Smartphone sichtbar</p>
				<p class="tablet">Dieser Absatz ist nur auf Tablets sichtbar</p>
				<p class="desktop">Dieser Absatz ist nur auf großen Monitoren sichtbar</p>
			</body>
		</html>
