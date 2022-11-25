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
					
					/* flex-basis */
					article{
						flex-grow: 0;
						flex-shrink: 1;
						flex-basis: auto; /* 15% */
					}

					/* Kurzschreibweise:
					* flex: 0 1 auto;
					*/
				</style>
			</head>
			<body>
				<h1>Flexbox - Ausdehnung kontrollieren - <code>flex-basis</code></h1>
				<main>
					<!--  main>(article>{Artikel $})*3 -->
					<article>Artikel 1 bliblablubb</article>
					<article>Artikel 2 Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas aliquid consequatur quo possimus non voluptatem. Beatae itaque autem explicabo culpa. Iure cupiditate quis maxime consequatur aperiam odio voluptas quasi! Adipisci!</article>
					<article>Artikel 3 Lorem, ipsum dolor sit amet consectetur adipisicing elit. Pariatur soluta deserunt, obcaecati tempore vitae veritatis doloremque nemo quis veniam, ipsam enim perferendis magni laudantium unde odio magnam ipsum voluptatem quidem.
					Illum quos, sunt dolor omnis ipsa doloribus delectus sit adipisci recusandae ducimus amet dignissimos molestiae at aperiam libero doloremque laborum alias eaque? Perspiciatis reprehenderit alias deleniti exercitationem sint perferendis veniam!</article>
				</main>
			</body>
		</html>
