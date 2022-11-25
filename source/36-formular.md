# Flexbox - Kontaktformular


		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Flexbox - Kontaktformular</title>
				<style>

					html{ box-sizing: border-box;}
					*, *::before, *::after {box-sizing: inherit;}

					body {
						font: 1rem/1.5 sans-serif;
						min-width: 320px;
						padding: 1rem;
						margin: auto ;
						background-color: rgb(126, 175, 126);
					}
					h1 {
						font-size: 1.5rem;
						margin-bottom: 1.5rem;
					}

					/* Basisformatierung */
					form { max-width: 500px; }
					form > div {margin-bottom: 1em;}

					/* zentrale Formatierung für alle Formular-Elemente */
					input,
					textarea,
					button{
					 font-size: 1.1rem;
					 line-height: normal; 
					 padding: 0.25rem 0.75rem;
					 border: none;   
					 margin: 0;
					} 

					input, textarea {
						background-color: rgb(222, 248, 235);
					}

					button {
						text-align: center;
						background-color: rgb(0, 0, 0);
						color: white;
						cursor: pointer;
					}

					button:hover,
					button:focus {
						background-color: red;
						color: white;
					}
					 /* Flex it */
					 form > div {
						display: flex;
						/* Automatische Anpassung der Seitenansicht */
						flex-flow: wrap;
					}

					input, 
					textarea,
					button {
						flex: 1 20rem;
					}
					 /* Das Eintragsfelder einheitlich groß */
					label {
						flex: 0 7rem;
					}

					/* Buttonbreite ändern ohne Media Query 
					* Buttonbreite durch Inhalt, rechts ausgerichtet 

					button {
						flex: none;
						margin-left: auto;
					}                                 */

				
					/* Buttonbreite mit Media Query ändern
					* Button so breit wie Eingabefelder
					* Wert für Media Query durch Ausprobieren ermitteln
					* Muss nicht unbedingt pixelgenau sein. 
					
					@media screen and (min-width: 464px) {
						button {
							margin-left: 7rem; 
						}
					}                                  */


				</style>
			</head>
			<body>
				<h1>Flexbox - Kontaktformular</h1>
				<form action="" class="kontaktformular">
					<!-- div>label+textarea -->
					<div>
						<label for="Besuchername">Ihr Name:</label>
						<input type="text" name="Besuchername" id="Besuchername" required>
					</div>


					<div><label for="Besucheremail">Ihre Email:</label>
						<input type="email" name="Besucheremail" id="Besucheremail" required>
					</div>

					<div><label for="Nachricht">Ihre Nachricht:</label>
						<textarea name="Nachricht" id="Nachricht" cols="20" rows="5"></textarea>
					</div>

					<div>
						<label></label>
						<button type="submit">Abschicken</button>
					</div>
				</form>
			</body>
		</html>
