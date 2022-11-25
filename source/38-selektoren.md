# Attributselektoren und Pseudoklassen


		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Attributselektoren und Pseudoklassen</title>
				<style>
				/* Attributselektoren */

					/* alle Links mit HREF-Attribut       
					a[href]{color: green;} 
					*/ 

					/* alle Links bei denen das href-Attribut den Wert "#start" hat */
					a[href='#start']{color: red;}
					a[href='#']{color: green;}

					/* Alle Absätze bei denen im Class Attribut die Zeichenkette "farbe" vorkommt */
					p[class~='farbe']{
							color: pink; 
							font-weight: bold;
							font-family:'Lucida Grande';
					}      

				/* Pseudoklassen */
					/* Das li-Element, welches das erste Kind ist */
					li:first-child { font-weight: bold;} 

					/* Das li-Element, welches das 3. Kind ist */
					li:nth-child(3) {color:navy}

					/* Das li-Element, welches das letzte Kind ist */
					li:last-child {font-style: italic;}

				</style>
			</head>
			<body>
				<h1><a target="_blank" href="https://developer.mozilla.org/en-US/docs/Web/CSS/Attribute_selectors">Attributselektoren</a> und Pseudoklassen</h1>

			<div>
				<a name="">Link ohne HREF</a><br>
				<a href="#">grüner Link</a><br>
				<a href="#start">roter Link</a><br>
				<a href="https://www.jena.de">Link nach Jena</a><br>
				<a href="dokumentation.pdf">Link zu einer PDF Datei</a><br>
				<p class="hinweis farbe essen">Absatz mit einer Klasse "farbe"</p><br>
			</div>

			<ul>
				<li>Erstens</li>
				<li>Zweitens</li>
				<li>Drittens</li>
				<li>Viertens</li>
			</ul>
			
			</body>
		</html>
