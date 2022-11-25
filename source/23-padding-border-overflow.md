# Innenabstand, Rahmen und Überlauf


				<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Innenabstand, Rahmen und Überlauf</title>
				<style>
					div{
						background-color: #fdafda;
						border: 2px solid #666;
						margin-bottom: 20px;
						/*Shorthand wie bei margin */
						padding: 10px;
					}
						/* Nachfahre-Selektor */
					#unten div {
						width: 280px;
						height: 100px;
						border-radius: 10%;
						}

					#ganzunten{
					width: 200px;
					height: 100px;
					overflow-y: scroll;
					}

				</style>
			</head>
			<body>
				<h1>Innenabstand, Rahmen und Überlauf</h1>

				<div>Lorem ipsum dolor sit amet consectetur adipisicing elit. Vitae cupiditate ab blanditiis, quis corrupti inventore veritatis error excepturi ipsam, vero a saepe! Blanditiis nihil nam laudantium quasi vero velit est.</div>

				<div id="unten"><div>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Inventore, sequi numquam ex sunt quis ipsa error. Non, veritatis omnis voluptate ut animi similique, architecto ullam illo, velit illum consequatur eveniet?</div>
				</div>

				<div id="ganzunten">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Voluptates placeat assumenda in laborum, tempora ipsa quo reiciendis neque. Quo impedit porro cupiditate, blanditiis facere in quidem perspiciatis perferendis repudiandae repellat!</div>


			</body>
		</html>
