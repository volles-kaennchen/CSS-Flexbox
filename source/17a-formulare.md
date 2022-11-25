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
				<form action="https://test.jaderbass.de/formtester.php" method="get"> <!-- GET -  praktisch aber alt, siehe Browser URL-->
					<ul>
						<p>Anrede:
							<label><input type="radio" name="anrede" value="Frau">Frau
							</label>
							<label><input type="radio" name="anrede" value="Herr">Herr
							</label>
							<label><input type="radio" name="anrede" value="Extrawurst">Blutgruppe Nutella
							</label>
							<label><input type="radio" name="anrede" value="GlitzerGlitzer">Ich bin ein Einhorn
							</label></p>

						<p><label for="vname">Vorname:</label><br> 
							<input type="text" name="vname" id="vname" maxlength="30" placeholder="Bitte Vornamen eingeben">  
						
						<p><label for="nname">Nachname*:</label><br>
							<input type="text" name="nname" id="nname" maxlength="60" placeholder="Bitte Nachnamen eingeben" required></p> 
						
						<p><label for="birthday">Birthday*:</label><br>
							<input type="date" id="birthday" name="birthday" required></p>
						
						<p><label for="email">E-Mail Adresse*:</label><br>
							<input type="email" name="email" id="email" placeholder="Bitte E-Mail eingeben" required></p>

						<p><label for="pw">Passwort*:</label><br>   
							<input type="pw" name="pw" id="pw" required>         
							<input type="hidden" name="versteckt" value="versteckte Botschaft"></p>

						<p>Team:
							<label><input type="checkbox" name="Team[]" value="Rot">Rot</label> 
							<label><input type="checkbox" name="Team[]" value="Röter">Röter</label> 
							<label><input type="checkbox" name="Team[]" value="Claudia Roth">Claudia Roth</label></p>
						
						<p><label for="streaming">Streaming Dienste:</label>
							<select name="streaming[]" id="streaming" multiple size="5">
								<optgroup label="Video">                              
									<option value="V-N">Netflix</option>              
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
							</select></p>

						<p><label for="url">Website:</label><br>
							<input type="url" name="url" id="url" placeholder="Website, Xing, Social Media.."></p>

						<p><label for="nachricht">Ihre Nachricht an uns:<br></label>
							<textarea name="nachricht" id="nachricht" cols="30" rows="10" required>Hallo, mein Anliegen ist...</textarea></p>
						
						<p><input type="submit" value="Übermitteln">
							<input type="reset" value="Zurücksetzen"></p>
					</ul>
				</form>
			</body>
		</html>
