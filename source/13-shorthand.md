# CSS_ Kurzschreibweisen

		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>CSS_ Kurzschreibweisen</title>

				<style>

					body {
						font-family: Verdana;
						font-size: 20px;
						/* Die 20pixel werden geerbt, ggf vom Browser überschrieben z.B. h1,h2.. */
					}
					h1 {
						border-bottom-style: solid;
						border-bottom-width: 10px;
						border-bottom-color: aqua;
						 /* Rahmen unter Überschrift mit EIgenschaft: 
						 Ausrichtung, Größe und Farbe*/
						
					}
					h2{
					   
					   border-bottom: 5px solid orangered; 
					   /*Shorthand Schreibweise im Tag*/
					}
					p{
						color:blueviolet;
					}
					span{
						color: rgb(37, 190, 114);
						font-style: italic;
					}
				</style>


			</head>
			<body>
				<h1>Shorthand - CSS in kurz</h1>

				<h2>Das ist eine Überschrift</h2>
				
				<p style="color:forestgreen;font-weight:bold;">Es gibt eine <span>CSS-Definition</span> direkt am HTML-Tag</p>
				<!-- ausstrecken mit span -->

				<p>In diesem Absatz wird die CSS-Definition aus dem internen Bereich umgesetzt.</p>

			</body>
		</html>
