# Fließende Boxen


		<!DOCTYPE html> 
		<html lang="de">
			<head>
				<meta charset="UTF-8">
				<meta http-equiv="X-UA-Compatible" content="IE=edge">
				<meta name="viewport" content="width=device-width, initial-scale=1.0" />
				<title>Fließende Boxen</title>

				<style>
					div { border: 1px solid #666;}

					#box1{
						width: 400px;
						height: 150px;
						background-color: #ac00347b;
						float: left}

					#box2{
						width: 300px;
						height: 120px;
						background-color: #ed9c537e;
						float: left}
					#box3{
						width: 250px;
						height: 100px;
						background-color: #cccca57e ;
						float: left}

					#box4{
						width: 400px;
						height: 150px;
						background-color: #ac00347b;
						float: right}

					#box5{
						width: 300px;
						height: 120px;
						background-color: #ed9c537e;
						float: right}
					#box6{
						width: 250px;
						height: 100px;
						background-color: #cccca57e ;
						float: right}

					#oben{
						clear: both;
						background-color: red;} 

					#mitte{
						clear: both;
						background-color: red;}
						 
					#unten{
						clear: both;
						background-color: red;} 



				</style>
			</head>
			<body>
				<h1>Fließende Boxen mit Float</h1>
				
				<div id="oben">oben</div>
				<!--  (#box$>{Box $})*3 -->
				<div id="box1">Box 1</div>
				<div id="box2">Box 2</div>
				<div id="box3">Box 3</div>

				<div id="mitte">mitte</div>

				<div id="box4">Box 4</div>
				<div id="box5">Box 5</div>
				<div id="box6">Box 6</div>

				<div id="unten">unten</div>
			</body>
		</html>
