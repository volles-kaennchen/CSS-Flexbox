# Textformatierung, Teil 2


		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Textformatierung, Teil 2</title>
			</head>
			<body>
				<h1>Textformatierung, Teil 2</h1>

				<!-- <Block Elemente -->
				<!-- Dazu gehören alle Absätze (p) und Überschriften (h1 bis h6), aber auch  
					 Bereiche (z.B <body). 
					 Sie erzeugen jeweils einen eigenen (rechteckigen) Rahmen, beginnen in der Regel immer (mit einem Abstand) in einer neuen "Zeile" und nehmen die komplette Breite ihres Eltern-Elementes ein. -->
				


				<!-- Emmet-Code: -->
				<!-- https://docs.emmet.io/-->
				<!-- (h1>{Überschrift, Ebene $})*6 UND p{Absatz}*1 -->

				<h1>Überschrift, Ebene 1</h1>
				<h2>Überschrift, Ebene 2</h2>
				<h3>Überschrift, Ebene 3</h3>
				<h4>Überschrift, Ebene 4</h4>
				<h5>Überschrift, Ebene 5</h5>
				<h6>Überschrift, Ebene 6</h6>
				<p>Absatz</p>

				<!-- Inline-Elemente -->
				<!-- Dazu gehören Text-Auszeichnungen (fett, kursiv, etc.) und Hyperlinks. Sie "laufen" in der Zeile mit dem Text und haben keine "eigene" Höhe bzw. Breite 
				
				WICHTIG! Regel: 
				Inline-Elemente müssen immer von einem Block-Element (außer <body>) umschlossen sein. Sie dürfen keine Block-Elemente als Kinder beinhalten.
				Ausnahme: Hyperlinks
				-->

				<p>Aufmerksamkeit steuern:<b> fetter Text (mit b)</b></p>
				<!-- strg + alt + t        type b + enter -->

				<p>Wichtigkeit und Dringlichkeit:<strong> fetter Text (mit strong)</strong></p>  
				<!-- strg + alt + t        type strong + enter -->
				<!-- Trennung von Wichtigem und Unwichtigem -->

				<p>Aussprache und Betonung: <i>kursiver Text (mit i)</i></p>
				<!-- strg + alt + t        type i + enter -->

				<p>Gewichtung: <em> kursiver Text (mit em).</em></p>

				<p>Gewichtung: <u> unterstrichener Text (mit u).</u></p>
				<!-- Sollte im Fließtext nicht benutzt werden, da Hyperlinks in der Regel unterstrichen dargestellt werden (User Experience). -->

				<p>text<sup>text hochgestellt</sup></p>
				<p>text<sub>text tiefgestellt</sub></p>
				<p>Dieser Satz<del>stimmt nicht</del>stimmt doch</p>

			</body>
		</html>
