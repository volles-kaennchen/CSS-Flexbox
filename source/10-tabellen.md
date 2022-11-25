# Tabellen

		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />

				<title>Tabellen</title>
			</head>
			<body>
				<h1>Tabellen</h1>
				<h2>einfache Tabellen</h2>

		<!-- das Attribut Border ist veraltet, wir stellen hiermit nur eine Rahmen dar. Richtig wäre dies mit css-->
				<table>
					<table border = "1">
						<tr>
							<td>Links</td>
							<td>Mitte</td>
							<td>Rechts</tr>
						</tr>
						<tr>
							<td>Links</td>
							<td>Mitte</td>
							<td>Rechts</tr>
						</tr>
				</table>

				<h1>Tabelle mit Kopfzeile</h1>

				<table>
					<table border = "1">
						<tr>
							<th>Datum</th>
							<th>Ort</th>
							<th>Ereignis</th>
						</tr>
						<tr>
							<td>Links</td>
							<td>Mitte</td>
							<td>Rechts</tr>
							<td>Links</td>
							<td>Mitte</td>
							<td>Rechts</tr>
						</tr>
				</table>

				<h2>Tabelle mit Sektionen</h2>

					<table border = "1">
						<thead>
							<th>Datum</th>
							<th>Ort</th>
							<th>Ereignis</th>
						</thead>
						<tbody>
							<tbody>
								<td>Links</td>
								<td>Mitte</td>
								<td>Rechts</tr>
							</tbody>
							<tfoot>
								<tr>
									<td>Links</td>
									<td>Mitte</td>
									<td>Rechts</tr>
								</tr>
							</tfoot>
						</tABLE>


						<H2>Tabellenbeschreibung</H2>
						<!-- table>(tr>td*2)*4 -->

						<table border = "1">
							<caption>Beschreibung der Tabelle</caption>
							<tr>
								<th>Name</th>
								<th>Farbe</th>
							</tr>
							<tr>
								<td>Anna</td>
								<td>Rot</td>
							</tr>
							<tr>
								<td>Tom</td>
								<td>Blau</td>
							</tr>
							<tr>
								<td>Sabrina</td>
								<td>Lila</td>
							</tr>
						</table>



						<h2>zellen verbinden</h2>
						
						<!-- (tr>td*3)*4 -->

					<table border = "1">
						<tr>
							<td colspan="3">z1z1</td>
						</tr>
						<tr>
							<td>z2z1</td>
							<td colspan="2">z2z2</td>
						</tr>
						<tr>
							<td rowspan="2">z3z1</td>
							<td>z3z2</td>
							<td>z3z3</td>
						</tr>
						<tr>
							<td>z4z2</td>
							<td>z4z3</td>
						</tr>
						<tr>
							<td colspan="2">z5z1</td>
							<td>z5z3</td>
						</tr>
					</table>
			</body>
		</html>
