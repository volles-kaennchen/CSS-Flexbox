# Klassen und ID-Selektoren

		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Klassen und ID-Selektoren</title>

				<style>
					body {
						font-family: sans-serif;
					}

				
					.rot {
						color: red;
					}
				   
					.gross{
						font-size: 200%;
					}
					 /* class wird in css style mit . angegeben z.B.: .rot .gross */
					 /* Eine class kann mehrfach verwendet werden */

					#einzug{
						text-indent: 80px;

					/* ID wird in css style mit # angegeben z.B.: #einzug #ausflug */
					/* Eine ID darf nur einmalig definiert werden */
					/* IDs werden in CSS jedoch höher gewertet als class */
					}
				</style>

			</head>
			<body>
				<h1>Weitere Selektoren</h1>

				<h2>Klassen und ID-Selektoren</h2>

				<h3 class="rot">Klassen-Selektoren</h3>

				<p class="gross">Das ist eine große Schrift.</p>
				<p class="rot">Das ist eine große, rote Schrift.</p>


				<h3>ID-Selektoren</h3>

				<p class=" rot gross">Alle Wege führen nach Rom!</p>
				<!-- hier greifen die klassen rot und gross, mehrere klassen können aufgelistet werden, zwischen ihnen muss ein leerzeichen stehen -->
				<!-- es greift die reihenfolge im stylesheet > steht im style z.B erst gross und dann rot, so wird die schrift erst vergrössert und dann rot eingefärbt  -->
				<p>Aber unter Umständen auch nach Erfurt.</p>

				<h3 class="gross">IDs und Klassen mischen.</h3>

				<p id="einzug" class="gross">Jetzt fällt mir nix mehr ein...</p>
			</body>
		</html>
