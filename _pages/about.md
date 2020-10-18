---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {box-sizing: border-box}
body {font-family: Verdana, sans-serif; margin:0}
.mySlides {display: none}
img {vertical-align: middle;}

/* Slideshow container */
.slideshow-container {
  max-width: 500px;
  position: relative;
  margin: auto;
}

/* Next & previous buttons */
.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  width: auto;
  padding: 16px;
  margin-top: -22px;
  color: white;
  font-weight: bold;
  font-size: 18px;
  transition: 0.6s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
}

/* Position the "next button" to the right */
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}

/* Caption text */
.text {
  color: #f2f2f2;
  font-size: 15px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* The dots/bullets/indicators */
.dot {
  cursor: pointer;
  height: 15px;
  width: 15px;
  margin: 0 2px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  transition: background-color 0.6s ease;
}

.active, .dot:hover {
  background-color: #717171;
}

/* Fading animation */
.fade {
  -webkit-animation-name: fade;
  -webkit-animation-duration: 1.5s;
  animation-name: fade;
  animation-duration: 1.5s;
}

@-webkit-keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

@keyframes fade {
  from {opacity: .4}
  to {opacity: 1}
}

/* On smaller screens, decrease text size */
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
</style>
</head>
<body>
<p> For the 2020-2021 academic year I am on sabbatical. </p>

<p>My current research is in computational inverse methods mainly applied to problems in the Geosciences, but also to more general imaging, signal processing and machine learning problems.  </p>

<div class="slideshow-container">

<div class="mySlides fade">
       <img src="../images/inCCP.png" alt="in CCP" style="width:100%;">
          </div>
          
<div class="mySlides fade">
      <center>  <img src="../images/mathbldg.jpg" alt="math building" style="width:100%;">
      <figcaption>Mathematics Building at Boise State</figcaption> </center>
          </div>
          
<div class="mySlides fade">
  <img src="../images/computing.png" alt="Computing program" style="width:100%;">
   <figcaption>https://boisestate.edu/computing</figcaption>
</div>

<div class="mySlides fade">
  <img src="../images/conductivity.png" alt="ERT and GPR Part 2" style="width:100%;">
  <figcaption>Domenzain et al, Geophysics, 2020 </figcaption>
</div>

<div class="mySlides fade">
  <center> <img src="../images/laplace_as_chi_2.png" alt="TV Chi2" width="341px" height="385px">
<figcaption>Mead, Inv. Prob. Imag., 2020 </figcaption> </center>
</div>

<div class="mySlides fade">
 <img src="../images/reg_choices.png" alt="Identifying structure" style="width:100%;">
 <figcaption>Hetrick, Inv. Prob. Sci. Eng., 2018</figcaption>
</div>

<div class="mySlides fade">
<img src="../images/mores.jpg" alt="Identifying structure" style="width:100%;">
 <figcaption>Treasure valley sunset</figcaption>
</div>

<div class="mySlides fade">
<img src="../images/sawtooths.jpg" alt="Identifying structure" style="width:100%;">
 <figcaption>Mountain biking in Sawtooths</figcaption>
</div>

<div class="mySlides fade">
<img src="../images/wasatch.jpg" alt="Identifying structure" style="width:60%;">
 <figcaption>Snowboarding in Wasatch</figcaption>
</div>

<div class="mySlides fade">
<img src="../images/melanie.jpg" alt="Identifying structure" style="width:60%;">
 <figcaption>Melanie</figcaption>
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span>
  <span class="dot" onclick="currentSlide(2)"></span>
  <span class="dot" onclick="currentSlide(3)"></span>
  <span class="dot" onclick="currentSlide(4)"></span>
  <span class="dot" onclick="currentSlide(5)"></span>
  <span class="dot" onclick="currentSlide(6)"></span>
  <span class="dot" onclick="currentSlide(7)"></span>
  <span class="dot" onclick="currentSlide(8)"></span>
  <span class="dot" onclick="currentSlide(9)"></span>
  <span class="dot" onclick="currentSlide(10)"></span>
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
}
</script>

</body>
</html>
 
