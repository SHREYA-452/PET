# PET
WEBSITE
#This file created by shreya 
<!DOCTYPE html>
<html>

	<!-- This is the head-->

	<head>
		<title>PetRescue</title>
		<link rel="stylesheet" type="text/css" href="style.css">
		<link rel="preconnect" href="https://fonts.gstatic.com"> 
		<link href="https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,300;0,400;0,900;1,700&display=swap" rel="stylesheet">
		

		<style>
			<!-- This is where we alter the button style and code. -->
			.button {
  			background-color: transparent;
  			border: none;
  			color: white;
  			padding: 80px 160px;
  			text-align: center;
  			transition-duration: 0.4s;
  			cursor: pointer;
			}

			.button5 {
  			color: white;
  			border: 2px solid white;
			background-color: transparent;
			position:absolute; left:900px; top:750px; 
			font-size: 20px;

			}

			.button5:hover {
  			background-color: #555555;
  			color: white;
			}


	
			<!-- This produces the general style for each code. -->
			<!-- This will hold styling for the three types of text. -->
			.container {
  				position: relative;
  				text-align: center;
 
				}

			<!-- These are specific references to each text, incase we want to modify each line individually. -->

			.firstline {
  			position: absolute;
  			top: 70px;
  			left: 70px;
			color: white;
			}

			.secondline {
  			position: absolute;
  			top: 300px;
  			left: 550px;
			color: white;
			font-size: 70px;
			}

			.thirdline {
  			position: absolute;
  			top: 375px;
  			left: 550px;
			color: white;
			font-size: 70px;
			}
			
			.fourthline {
  			position: absolute;
  			top: 450px;
  			left: 550px;
			color: white;
			font-size: 70px;
			}
			
			.fifthline {
  			position: absolute;
  			top: 700px;
  			left: 670px;
			color: #D3D3D3;
			font-size: 30px;
			}

			
		</style>

		
	</head>






	<!-- This is the body -->
	<body>
		<div>
				<ul id ="navigation">
					<li><a href="homepage.html">HOME</a></li>
					<li><a href="Services.html">SERVICES</a></li>
					<li><a href="FAQ.html">FAQ</a></li>
					<li><a href="About.html">ABOUT</a></li>
				</ul>
		</div>

		<!-- This takes care of the logo and positioning. -->

  		<img src="logo.png" width="300" height="350" style="position:absolute; left:250px; top:250px;">

		<!-- This creates a container filled with 4 types of text. --> 

		<div class="container">
			<div class="firstline"></div>
  			<p><div class="secondline">Care for me. </div></p>
  			<h2><div class="thirdline">I'll care</div></h2>
			<div class="fourthline">For you.</div>
			<div class="fifthline">Click HERE if you want to help them get a home!</div>

		</div>


		<!-- Add Button -->
		<button class="button button5">I WANT A PET</button>


		
	</body>










</html>
