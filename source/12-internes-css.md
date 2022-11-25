# CSS im Dokument nutzen

		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />

				<title>CSS im Dokument nutzen</title>

				<style> 
					h1, h2{
						color: rgb(124, 48, 224);
						background-color: antiquewhite;
						font-family: 'Verdana';
					}

					h2{
						color: rgb(226, 123, 27);
						background-color: transparent;
					}
					/* Der letzte Wert gewinnt - sprich h2 wird erst blau gefärbt und sieht anhand des skriptes im nachhinein, das diese grün sein soll. So spart man sich doppelte styles..*/

									/* 
									Standard Syntax
												Selektor {
													eigenschaft: wert;
													eigenschaft: weiterer wert
												}
									*/

					p{
						color: rgb(64, 162, 219);
						background-color: rgb(199, 223, 183);
						font-family: 'sans-serif';
					}

				</style>

			</head>

			<body>
				<h1>CSS im Dokument nutzen</h1>
				<h2>CSS Ist für das Layout zuständig</h2>

				<p>Hier kommt ein Absatz</p>
			</body>
		</html>
