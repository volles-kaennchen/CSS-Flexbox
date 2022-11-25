# Navigation

		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Navigation</title>

				<style>
					body{
						font-family: sans-serif;
						background-color: black;
					}

					/* Listen Bullets ausschalten */
					nav > ul {
						list-style: none;
						/* Hintergrundfarbe der Liste */
						background-color: hotpink;
						/* Mit Flexbox die List Items nebeneinander */
						display: flex;
					}
					 
					/* Abstände */
					nav > ul > li {margin-right: 10px;}

					/* Schriftart/farbe für Links*/
					nav > ul > li > a {
						/* Unterstreichung der Links entfernen */
						text-decoration: none;

						padding: 10px 5px;
						/* damit das Padding Wirkung zeigt */
						display: inline-block;
						color: azure;

					}
					
					/* normaler Link (unbesucht)*/ 
					nav > ul > li > a:link
					/* besuchter Link */ 
					nav > ul > li > a:visited
					/* aktiver Link */ 
					nav > ul > li > a:active
					/* Link hat den Focus */ 
					nav > ul > li > a:focus {color: white;}
					/* Mouseover Link */
					nav > ul > li > a:hover{
							background-color: rgb(255, 167, 208);
							color: black;
					}

					nav > ul > li:last-child {
						margin-left: auto;
					}
				</style>

			</head>
			<body>
				<nav class="site-nav">
					<ul>
						<!-- (li>a)*7 -->
						<li><a href="#"> Startseite</a></li>
						<li><a href="#" target="_blank"> Triopse</a></li>
						<li><a href="#" target="_blank"> Schnecken</a></li>
						<li><a href="#" target="_blank"> Nelen</a></li>
						<li><a href="#" target="_blank"> Fauna</a></li>
						<li><a href="#" target="_blank"> Kontakt</a></li>
						<li><a href="#" target="_blank"> Impressum</a></li>
					</ul>
				</nav>
			</body>
		</html>
