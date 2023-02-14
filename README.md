My porfolio.
<!DOCTYPE HTML>
<head>
  <title>Lianne O'Malley porfolio.</title>
  
  <link rel="stylesheet" type="text/css"  href="StyleSheet.css">
</head>
 <!-- <script src="JavaScriptProflio.js"> </script> -->
<meta charset="utf-8>"
<body>

<nav class="topNavBar">
    <a href="HomePage.html" class="homeLink">HOME</a>
    <a href="C:\Users\liann\Desktop\Pratice CV 2\aboutMePage.html" class="aboutMeLink">ABOUT ME</a>
    <a href="#" class="theLetterL">&#9733;</a>
    <a href="WorkHomePage.html" class="workLink">WORK</a>
    <a href="CvPage.html" class ="cvLink">CV</a>
  <!-- work is previous work link-->

<!-- Start of the Contact code -->
<!-- open the form button-->
    <button id="myBtn">CONTACT</button>

    <div id="theForm" class="form">
    <div class="insideTheForm">
       <header class="formHeader">
	   <span class="close">CLOSE</span>
	   </header>
	
          <h3> Hi, want to contact me? </h3>

  <hr></hr>
	<a href="tel:+447535271760" class="phone"> <img src="Images\phoneImage.png"style="width:25px;height:25px; alt="phone picture">Phone Me</a>
	<!-- Even above or should just place number-->
     <br>
	 <br>
   <a href="mailto:liannemarie2004@hotmail.com" class="mailto"> <img src="Images\emailMe.jpg" style="width:25px;height:25px; alt="email me icon">Email me </a>
   <!-- If user click on the email and send me message then goes back on the website i need a thank you box as the contact pop up box stay on -->
   <!--<label for="emailMe">Email Me </label>-->
   <!--<input type="text" id="emailMe"/>-->
   <h3> Barnsley, UK </h3>
   <br>
   </nav>
</div>
</div>
  <!-- end of the contact me code -->
<button onclick="topFunction()" id="topBtn" title="go to the top"><big><big>&#129049;</big></big></button>

<br>
<br>

<div class="homeScreenTop1">
<!-- need image to resize when user min the screen -->
  <img src="tyrographPratice6.jpg">

</div>

<div class="homeScreenPage2">
  <img src="Images\photoOfMe2.gif" alt="photoOfMe" class="photoOfMe"></img>
  <pre class="aboutMeText">

 <!--dont remove the whitespacing before the text and after-->
  Who I am?
  Hey, I'm Lianne, I have a passion for design 
  and like creating innovative ideas that leave 
  an impression. I class myself as a multidisciplinary 
  designer,as I can challenge myself to anything whether its
  product design or digital design including the code
  or if it just creating a simple beautiful logo. 
  I'm enthusiastic about user experience design and
  love to speak with users to understand and fulfil 
  their needs, using their insights to create a design 
  that has a high degree of both usability and desirability.
  <a href="aboutMePage" class="LinkMore"> Want to know more about me click here :)</a>
  </pre>

</div>

 <br>

<!-- Skills section -->
 <h1  style="text-align:center" class="SkillsHeader">Skills</h3>
 <br>
 <br>
 <br>
 <br>
 <div class="Skills">
   <!-- good idea if user rollover or click the image of say research for example a little pop up could come up saying for example research is great throughout a project, at the start it is important to see what existed.-->
	<br>
	<br>
   <img src="Images/Skills image/PhotoShopImage2.jpg" class="photoshopImage"> </img>
   <img src="Images/Skills image/CodingText.jpg" class="codeText"> </img>
	<img src="Images/Skills image/fidPhoto2.jpg" class="prototypeImage"> </img>
	<img src="Images/Skills image/graph2.jpg" class="Evaluations"> </img>
	<img src="Images/Skills image/questionnaireImage2.jpg" class ="questionnaireImage"></img>
	<img src="Images/Skills image/endImage2.jpg" class="endSkill"> </img>
	<img src="Images/Skills image/uxImage2.jpg" class="Ux"> </img>
	<img src="Images/Skills image/microsoftOffice2.jpg" class="microsoftImage"></img>
			
 </div>
 
<div class="work">
  <a href="C:\Users\liann\Desktop\Pratice CV 2\AppPage.html"><img src="Images/InterFaceSketchesOfApp.jpg" alt="interface sketch" class="interfacePic"></a>
  <a href="C:\Users\liann\Desktop\Pratice CV 2\SmartPlate.html"><img src="C:\Users\liann\Desktop\Pratice CV 2\Images\smartPlateImage.jpg" alt="Smart Plate" class="SmartPlate"></a>
  <a href="C:\Users\liann\Desktop\Pratice CV 2\CyprusPage.html"><img src="C:\Users\liann\Desktop\Pratice CV 2\Images\CyrpusImage.jpg" class="HeuristicEvualuation" alt="Heuristic Evualuation"></a>
  <a href="WebsiteDesign.html"><img src="Images\clubIt.jpg" class="WebsiteDesign" alt="website design"></a>
</div>

 
 <div class="textUnderWorkPic">
   <a href="AppPage.html"><p class="text1"> App Project.</p></a>
   <a href="SmartPlate.html"><p class="text2">Smart Plate Project.</p></a>
   <a href="CyprusPage.html"><p class="text3">Heuristic Evaluation.</p></a>
   <a href="WebsiteDesign.html"><p class="text4">WebsiteDesign</p></a>
</div>

<footer>
<!-- maybe be cheeky with click me (click me) and if click its says something like oh you want to contact me cool, just click on my number or email ;)-->

<!-- footer-->
<div class="contactMeFooter">
    <h4> Hi, Want to contact me?  (Click me) <img src="footerArrow.jpg" alt="curved arrow" class="curvedArrow"> </h4></img>
	
	<a href="mailto:liannemarie2004@hotmail.com"style="color:black;text-decoration:none;"><button class="EButton">Email Me</button></a>
	<a href="tel:+447535271760"style="color:black;text-decoration:none;"><button class="PButton">Phone Me</button></a>

<a href="https://www.linkedin.com/in/lianne-o-malley-a5b729133/"> <img src="Images/LinkedIn.png" alt="linkedIn icon" class="linkedIcon"> </img></a> 

<a href="https://github.com/LittleLianne"><img src="Images/GitHub.jpg" alt="Github icon" class="GitHubIcon"></img></a>
</div>

</footer>

<!-- end of footer-->


<script>

var modal = document.getElementById("theForm");

// Get the button that opens the form
var btn = document.getElementById("myBtn");

// uses the <span> to close the form
var span = document.getElementsByClassName("close")[0];

// When the user clicks on the button, open the modal
btn.onclick = function() {
  modal.style.display = "block";
}

// When the user clicks on <span> (x), close the modal
span.onclick = function() {
  modal.style.display = "none";
}

// When the user clicks anywhere outside of the modal, close it
window.onclick = function(event) {
  if (event.target == modal) {
    modal.style.display = "none";
  }
}
</script>

<!-- script for to the top button-->
<script>

  let mybutton = document.getElementById("topBtn");

  window.onscroll = function() {scrollFunction()};

function scrollFunction() {
  if (document.body.scrollTop > 20 || document.documentElement.scrollTop > 20) {
    mybutton.style.display = "block";
  } else {
    mybutton.style.display = "none";
  }
}

function topFunction() {
  document.body.scrollTop = 0;
  document.documentElement.scrollTop = 0;
}
</script>
<!-- end of the script for to the top button-->



</body>
</html>
