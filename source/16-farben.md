# Farben mit CSS


		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Farben mit CSS</title>

				<style>
					div {
						border: 3px solid gray;
						margin-bottom: 18px;    /* mb8p */ 
						padding: 20px;          /* p20p */
						/* PIXEL NICHT PROZENT!*/
						background-color: rgb(136, 180, 75);
					}
					
					#erster_abschnitt{
						color: #fff;
						background-color: hsl(129, 36%, 22%); 
						/* wert (hue) - winkel (saturation) - helligkeit (lightness) */
					}
					#zweiter_abschnitt{
						color: #3a3abb;
						background-color: beige;
					}

				</style>
			</head>
			<body>
				<h1>Farben mit CSS</h1>

				<!-- #erster_abschnitt      hier wird ein Container erstellt -->
				<!-- .abschnitt      hier wird ein Container erstellt -->

				<!-- z.B. div#erster_abschnitt>(p>lorem)*3 -->

				<div id="erster_abschnitt">
					<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Porro est cum quae mollitia ex corporis sapiente neque, excepturi dolorem voluptatibus sunt, possimus accusamus at, magni error vel! Modi, minima tenetur.</p>
					<p>Animi, vero! Quos, culpa nostrum mollitia odit quidem ipsum voluptatem cumque ea facere iure ipsa reiciendis iste dolores omnis corporis libero. Veniam beatae doloribus harum et debitis optio quisquam itaque.</p>
				</div>

				<div id="zweiter_abschnitt">
					<p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Itaque, accusamus quidem nihil, fuga incidunt eaque ipsam ullam tempore enim quas eligendi. Facere porro dolorum soluta alias nulla corrupti, ipsum praesentium.</p>
					<p>Doloribus aspernatur laboriosam voluptates aliquam corrupti voluptas aut cupiditate unde sunt dicta nihil ipsum excepturi, voluptatem alias magni? Quae at itaque vero quidem dolorem nostrum, iste voluptatibus. Magni, praesentium cum.</p>
				</div>

			</body>
		</html>
