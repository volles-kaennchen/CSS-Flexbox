# Elemente positionieren


		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Elemente positionieren</title>
				<style>
					body{margin: 0;} /* die position beginnt ganz links */
					#eins{
						width: 100px;
						height: 200px;
						background-color: greenyellow;

						 /* position: relative;folge-elemente bleiben in seiner form */
						/* left: 250px;
						top: 50px; */
					
						/*position: absolute; entfernt elmenent aus position, platz wird frei für folgeelemente - dies rutscht nach */
						/* position: absolute oben unten | links rechts
						left: 250px; - nach links um 250px verrutschen 
						top: 50px; - nach unten um 50px verrutschen */
					}

					#zwei{
						width: 400px;
						height: 2000px;
						background-color: rgb(255, 99, 71,.466);

						position: relative;   
						/*  top: 50px;
							left: 50px;

						position: absolute;
						top: 50px;
						left: 50px; */
					}

					#drei{
						width: 150px;
						height: 100px;
						background-color: lightblue;
						/* position: absolute;
						top: 50px;
						left: 50px; 

						position: fixed;            egal was eltern-element macht
						right: 20px;
						bottom: 20px;*/

						position: sticky;
						left: 50px;
						top: 50px;
					}
				</style>
			</head>
			<body>
				<div id="eins">Eins</div>
				<div id="zwei">
					<div id="drei">Drei</div>
					Zwei
				</div>
			</body>
		</html>
