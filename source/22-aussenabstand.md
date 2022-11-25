# Außenabstand mit margin	


			<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Außenabstand mit margin</title>
				<style>
					div{
						height: 70px;
					}
					#eins{
						background-color: #ac0035;
						margin-bottom: 15px;
					}
					#zwei{
						background-color: #ed9c53;
						/* margin-top: 20px;
						margin-right: 30px;
						margin-bottom: 40px;
						margin-left: 35px; */

					/*
						margin: 20px; alle 4 seiten gleicher abstand
						margin: 20px 40px; 1. Wert vertikal - 2. Wert horizontal 
						margin: 20px 40px 30px; 1. Wert vertikal - 2. Wert horizontal 3. untere Abstände
						margin: 20px 40px 30px 50px; 1. Wert obere, dann im Uhrzeigersinn  */
					}
					#drei{
						background-color: #cccca5;
					}
				</style>
			</head>
			<body>
				<h1>Außenabstand mit margin</h1>

				<div id="eins"></div>
				<div id="zwei"></div>
				<div id="drei"></div>
			</body>
		</html>
