# Flexbox Order


		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Flexbox Order</title>
				<style>
					body{ display: flex; flex-direction: column;} /* flex-direction: column; */
					header,
					nav,
					main,
					footer{
					height: 150px;
					margin-bottom: 5px;
					border: 1px solid black;
					}

					header, 
					nav{ order: -1;}
					
					header{background-color: red;}
					nav{background-color: green;}
					main{background-color: blue;}
					footer{background-color: yellow;}
				</style>
			</head>
			<body>
				<header>HEADER</header>
				<nav>NAVIGATION</nav>
				<main>MAIN</main>
				<footer>FOOTER</footer>
			</body>
		</html>
