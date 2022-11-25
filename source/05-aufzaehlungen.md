# Ungeordnete Listen: Aufzählungen

		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Ungeordnete Listen: Aufzählungen</title>
			</head>
			<body>
				<h1>Ungeordnete Listen: Aufzählungen</h1>

				<ul>
					<!-- list items with dots --> 
					<li>Visual Studio Code</li>
					<li>Sublime</li>
					<li>Notepad ++</li>
				</ul>

				<ol>
					<!-- list items with number --> 
					<li>Visual Studio Code</li>
					<li>Sublime</li>
					<li>Notepad ++</li>
				</ol>

				<p><Strong>Regel:</Strong><br>Direkte Kind-Elemente einer Liste (ul, ol, dl) durfen <b>ausschließlich</b> li-Elemente sein!</p>

				<p>Innerhalb der li-Elemente dürfen dann aber andere HTML-Elemente platziert werden.</p>

				<p>Alle Listen-Elemente sind Block-Elemente.</p>

				<p>Ungeordnete Listen werden zur Erzeugung von Navigationsleisten / Menüleisten benutzt.</p>

				<!--Verschachtelte Listen einfach -->
				<h2>Verschachtelte Listen</h2>
					<ul>
						<li>HTML</li>
								<ol>
									<li>Maskieren</li>
									<li>Tabellen</li>
								</ol>    
						<li>CSS</li>
						<li>Java Script</li>
						<li>Frameworks</li>
						<li>PHP</li>
					</ul>

				<!-- Listenstruktur über Emmet darstellen -->
				<!-- 1. einfache Liste + 3 Aufzählungen z.B. ul>li*3 oder li*4 -->

				<ol>
					<!-- list items with number --> 
					<li>Visual Studio Code</li>
					<li>Sublime</li>
					<li>Notepad ++</li>
				</ol>

				 <!--Verschachtelte Listen -->
				 <h2>Verschachtelte Listen</h2>
				 <ul>
					 <li>HTML</li>
						 <ul>
							 <li>Grundlagen</li>
							 <li>Textformatierung</li>
								 <ul>
									 <li>Absätze</li>
									 <ul>
										 <li>Inline-Elemente</li>
									 </ul>
								 </ul>
							 <li>Maskieren</li>
							 <li>Tabellen</li>
						 </ul>
					 <li>CSS</li>
					 <li>Java Script</li>
					 <li>Frameworks</li>
					 <li>PHP</li>
				 </ul>
			
				<!-- z.B ul>(li>ul>li*3)+li*4 -->

				 <ul>
					<li> HTML
						<ul>
							<li>Grundlagen</li>
							<li>Textformatierung</li>
							<li>Absätze</li>
						</ul>
					</li>
					<li> Inhalt einfügen</li>
					<li> Inhalt einfügen</li>
					<li>Inhalt einfügen</li>
					<li>Inhalt einfügen</li>
				 </ul>
			</body>
		</html>
