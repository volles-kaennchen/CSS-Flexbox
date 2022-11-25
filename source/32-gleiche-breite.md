# Flexbox - Ausdehnung


		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Flexbox - Ausdehnung - display:flex mit wenig Inhalt</title>
				<style>
					/* Grundformatierung */
					main{
						max-width: 720px;
						background: #f1f1f1;
						padding: 0.5rem;
						border: 1px solid #ccc;
					}
					article:nth-child(1){ background: blue;}
					article:nth-child(2){ background: gray;}
					article:nth-child(3){ background: red;}

					/* Flexbox */
					main {
						display: flex;
						min-height: 10rem;
					}

					article {
						padding: 0.5rem;
						border-radius: .5rem;
						margin: 0.5rem;
					}
				</style>
			</head>
			<body>
				<h1>Flexbox - Ausdehnung - display:flex mit wenig Inhalt</h1>
				<main>
					<!--  main>(article>{Artikel $})*3 -->
					<article>Artikel 1</article>
					<article>Artikel 2</article>
					<article>Artikel 3</article>
				</main>
			</body>
		</html>
