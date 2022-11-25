# Maßeinheiten in CSS


		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />

				<title>Maßeinheiten in CSS</title>
				<meta name="description" content="Externe Stylesheets">

				<style>
					
				/* 
				*** Absolute Maßeinheit ***

					Pixel (px)
					Punkt (pt)
					Inch (in)
					Millimeter (mm)
					Zentimeter (cm)

				*** Relative Maßeinheiten ***

					Prozent (%)
						bezieht sich auf die Größenangabe des übergeordneten Eltern-Elementes

					Ems (em, rem)
						bezieht sich auf die Breite des Buchstaben "m" ....

						em: .... des Übergeordneten Elter-Elements (ähnlicher Prozent) in
							Abhängigkeit von der Schriftgröße dieses Elementes.

						rem: .... des Root-Elementes (html).
					
					Exes (ex)
						wie bei em, nur ist hier die Basis des kleinen "x".

					Viewportbreite,
					Viewporthöhe (vw, vh)
						bezieht sich auf die Größe des sichtbaren Bereiches des Monitors
				*/

					html {font-size: 32px;}

					div {font-size: 24px;
						border: 2px solid greenyellow;
						width: 50vw;
						height: 50%;}

					p {font-size: 0.5em;}
					
					.basis {font-size: 0.5em;}

				</style>


			</head>
			<body>
				<h1>Maßeinheiten in CSS</h1>
				<p>Standard-Absatz</p>

				<div>
					<h1>Überschrift</h1>
					<p>Standard-Absatz</p>
					<p class="basis">Hier kommt ein rem-Absatz.</p>
				</div>
			</body>
		</html>
