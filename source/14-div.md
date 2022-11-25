# DIVs - Bereiche ohne Aufgabe

		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>DIVs - Bereiche ohne Aufgabe</title>
				<style>
					div{
						border: 3px solid rgb(20, 124, 60);
						background-color: rgb(154, 179, 155);
						width: 250px; /* div breite */
						margin-bottom: 18px; /* Außenabstand unten */
						padding: 20px; /* Abstand des inneren Textes */
					}

				</style>
			</head>
			<body>     
					<h1>DIVs - kleine lustige Kästchen für das Layout</h1>

				<div>   
				<p><i>Wir arbeiten hier mit DIVs, also Bereichen ohne semantische Bedeutung</i></p>
				<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae deserunt officiis eius, impedit excepturi quidem at cum reprehenderit quasi temporibus ipsa tempore facilis vel earum? At, porro? At, expedita nobis!</p>
				</div>

				<div>
				<!-- z.B. div>(p>lorem)*3 -->
					<h2>Lorem</h2>
					<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem similique fugit assumenda id quae, rem perferendis expedita repellat ipsam, quam esse voluptate nam vero ipsa voluptatibus omnis! Reprehenderit, expedita exercitationem?</p>

					<p>Dolorem quibusdam hic veritatis repellat ad harum illum quod esse exercitationem quasi impedit fugiat iste facere vero magnam numquam ea, corporis qui dolore mollitia deserunt. Praesentium modi unde numquam veritatis!</p>

					<p>Voluptate laboriosam eveniet odit, qui porro, accusantium reiciendis praesentium sint possimus numquam officia corrupti et repudiandae reprehenderit dolorem recusandae animi, quasi dolorum molestias. Excepturi tempore quo culpa officia, soluta eum.</p>
				</div>

				<div>   
					<p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Molestiae deserunt officiis eius, impedit excepturi quidem at cum reprehenderit quasi temporibus ipsa tempore facilis vel earum? At, porro? At, expedita nobis!</p>
					</div>
			</body>
		</html>
