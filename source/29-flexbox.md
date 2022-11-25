# Flexbox nutzen


		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Flexbox nutzen</title>
				<style>
					/* Das Sternchen "*" kann als Platzhalter verwendet werden */
					body, * {
						font-family: sans-serif;
						font-size: 16px;
						margin: 0;
					}

					h1{
						margin: 10px 8px;
					}
					.flexcontainer {
						width: 600px;
						padding: 4px;
						border: 1px solid gray;
						margin-bottom: 5px;
						margin-left: 8px;

						display: flex;
					}

					.flexitem{
						padding: 10px;
						margin-bottom: 5px;
						margin-left: 5px;
						background-color: chocolate;
					}
				</style>
			</head>
			<body>
				<h1>Flexbox nutzen</h1>
				<div class="flexcontainer">
					<div class="flexitem">Item 1</div>     <!--.flexcontainer>(.flexitem>{Item $})+5 -->
					<div class="flexitem">Item 2</div>
					<div class="flexitem">Item 3</div>
					<div class="flexitem">Item 4</div>
					<div class="flexitem">Item 5</div>
				</div>
			</body>
		</html>
