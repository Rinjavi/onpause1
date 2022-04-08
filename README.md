# onpause1
<html> file 
  
  <div id="outer1">
		<div id="slideContainer1">
			<img src="Image-Folder/IMG_1053.jpg" alt="Me at the Birthay party">
			<img src="Image-Folder/IMG_0069.jpg" alt="Me with Youwa">
			<img src="Image-Folder/9059964300705860574_IMG_0254.jpg" alt="Me at Westchester Flames">
			<img src="Image-Folder/IMG_0105.jpg" alt="Me at the game">
			<img src="Image-Folder/IMG_0019.jpg" alt="Me at NYCFC19">
			<img src="Image-Folder/IMG_2432.jpg" alt="Me with my lil bro">
			<img src="Image-Folder/IMG_2435.jpg" alt="Me kicking the ball">
			<img src="Image-Folder/IMG_0066.jpg" alt="Me at the prom">
			<img src="Image-Folder/72d85e6d-2245-4624-8cd7-8c0d3b1975f7.jpg" alt="Me at the academy">
			<img src="Image-Folder/IMG_1999.jpg" alt="Me with my family">
			<img src="Image-Folder/0cc71071-839a-4abf-9ea3-24d53c23a416.jpg" alt="Me at teammates in Spain">
			<img src="Image-Folder/IMG_2451.jpg" alt="Me with my squad">
		</div>
    
    
  CSS file 
    
    
#outer1 {
	width: 500px;
	height: 400px;
	overflow: hidden;
	border: 5px solid black;
	border-radius: 25px;
	margin-left: 35%;
	margin-bottom: 20px;
}

#slideContainer1 {
	position: relative;
	width: 6000px;
	animation-name: rinSlider1;
	animation-duration: 60s;
	animation-iteration-count: infinite;
}

img {
	float: left;
}

@keyframes rinSlider1 {
	0% {
		left: 0px;
	}

	5% {
		left: 0px;
	}

	10%{
		left: -500px;
	}

	15% {
		left: -500px;
	}...........
