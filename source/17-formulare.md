# Formulare

		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Formulare</title>

			</head>

				<h1>Formular</h1>

				<!-- form-get (URL Query)      form-post (Header) -->
				<!-- "action" - es muss ein Skript angegeben werden, damit die Daten verarbeitet werden können -->
				<!-- Beginn und Ende <form></form> -->

				<form action="https://test.jaderbass.de/formtester.php" method="post">
				<!-- ein formular ohne layout: -->
				
				<ul>
						<p>Anrede:
							<label><input type="radio" name="anrede" value="Frau">Frau
							</label>
							<!-- values wert-->

							<label><input type="radio" name="anrede" value="Herr">Herr
							</label>

							<label><input type="radio" name="anrede" value="Extrawurst">Blutgruppe Nutella
							</label>

							<label><input type="radio" name="anrede" value="GlitzerGlitzer">Ich bin ein Einhorn
							</label>
						</p> <!-- semantisch ohne label-->

						<p>
					
							<label for="vname">Vorname:</label><br> <!-- "Label" bezeeichnet die Formularelemente-->
							<input type="text" name="vname" id="vname" maxlength="30" placeholder="Bitte Vornamen eingeben">  
							<!-- "input" definiert die Aufgabe des Feldes und seine 2 Attribute "name" (übermittlung) "id" (Zusammenhang / Verbindung) -->
							<!-- maxlength="30"     definiert die Länge der Eingabe in das jeweilige Feld-->
							<!-- placeholder gibt zb an "bitte vornamen angeben"-->
						</p>

						<p>
							<label for="nname">Nachname*:</label><br>
							<input type="text" name="nname" id="nname" maxlength="60" placeholder="Bitte Nachnamen eingeben" required>  
							<!-- ist kein "type" vorhanden oder falsch angegeben, wird automatisch ein Textfeld für die Eingabe generiert -->
							<!-- mit "required" generieren wir ein Pflichtfeld-->
						</p> 

						<p>
							<label for="birthday">Birthday*:</label><br>
							<input type="date" id="birthday" name="birthday" required>
						</p>

						<p>
							<label for="email">E-Mail Adresse*:</label><br>
							<input type="email" name="email" id="email" placeholder="Bitte E-Mail eingeben" required>

							<!-- Email Feld (übermittelt die Daten nur wenn Email mit @ vorhanden ist, - keine genaue Prüfung)-->
						</p> 

						<p>
							<label for="pw">Passwort*:</label><br>   
							<!--passwort kommt immer im klartext an (unsicher!) es benötigt eine DB oder verschlüsselte Verbindung --> 
							<input type="pw" name="pw" id="pw" required>              <!--required-->
							<input type="hidden" name="versteckt" value="versteckte Botschaft">
						</p>

						<p>Team:
							<label><input type="checkbox" name="Team[]" value="Rot">Rot</label> 
							<label><input type="checkbox" name="Team[]" value="Röter">Röter</label> 
							<label><input type="checkbox" name="Team[]" value="Claudia Roth">Claudia Roth</label>
							<!-- wenn wir [] unter Name angeben, können mehrere Ergebnisse ausgewählt und übermittelt werden -->
						</p>

						<p> <!-- drop down menue erstellen -->
							<label for="streaming">Streaming Dienste:</label>
							<select name="streaming[]" id="streaming" multiple size="5">    <!-- Mehrere Auswahlmöglichkeiten mit "multiple" + "[]" in name="   hier einfügen  "-->
							<optgroup label="Video">                               <!-- optgroup name der gruppe angeben -->
								<option value="V-N">Netflix</option>               <!-- eine  value=""    kann bei <option   > eingefügt werden-->
								<option value="V-A">Amazon Prime</option>
								<option value="V-D">Disney +</option>
								<option value="V-W">WOW</option>
							</optgroup>   
							<optgroup label="Apps">   
								<option value="A-S">Spotify</option>
								<option value="A-D">Deezer</option>
								<option value="A-Y">YouTube</option>
								<option value="A-A">Amazon Music</option>
							</optgroup>    
							</select>
						</p>

						<p>
							<label for="url">Website:</label><br>
							<input type="url" name="url" id="url" placeholder="Website, Xing, Social Media..">
						</p>

						<p>
							<label for="nachricht">Ihre Nachricht an uns:<br></label>
							<textarea name="nachricht" id="nachricht" cols="30" rows="10" required>Hallo, mein Anliegen ist...</textarea>
							<!-- hier kann man einen placeholder="" einfügen oder einen personalisierten Text zwischen >schreiben<      -->
							<!-- es ist darauf zu achten das </textarea> nicht in einer neuen Zeile steht - dies erzeugt im Textfeld eine Formatierung -->
						</p>

						<p>
							<input type="submit" value="Übermitteln">
							<!-- Button "Absenden" erstellen - Buttontext kommt in value="" kann auch weggelassen werden,der Brwoser schreibt dann den Standard Wert  -->
							<input type="reset" value="Zurücksetzen">
							<!-- Button "Zurücksetzen" erstellen - Dok wird auf seinen Anfangszustand zurück gesetzt -->
						</p>


				</ul>


				</form>
			</body>
		</html>
