---
permalink: /
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<html lang="en">
  <head>
  <title>Bootstrap Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
</head>
<body>

<div class="container">
  <div id="myCarousel" class="carousel slide" data-ride="carousel">
    <!-- Indicators -->
    <ol class="carousel-indicators">
      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#myCarousel" data-slide-to="1"></li>
      <li data-target="#myCarousel" data-slide-to="2"></li>
    </ol>
  
<!-- Wrapper for slides -->
<div class="carousel-inner">
      <div class="item active">
      <img src="../images/mathbldg.jpg" alt="math building" style="width:100%;" width="193" height="130">
          </div>
          
<div class="item">
      <img src="../images/computing.png" alt="Computing program" style="width:100%;">
        <figcaption>https://boisestate.edu/computing</figcaption>
      </div>

<div class="item">
<img src="../images/conductivity.png" alt="ERT and GPR Part 2" style="width:100%;">
  <figcaption> Domenzain et al, Geophysics, 2020 </figcaption>
      </div>

<div class="item">
<img src="../images/reg_choices.png" alt="Identifying structure" style="width:100%;">
  <figcaption> Hetrick et al, Inv. Prob. Sci. Eng., 2018</figcaption>
      </div>
      <div class="item">
      <img src="../images/laplace_as_chi_2.png" alt="TV Chi2" style="width:50%;">
        <figcaption> Mead, Inv. Prob. Imag., 2020</figcaption>
            </div>
    </div>

<!-- Left and right controls -->
<a class="left carousel-control" href="#myCarousel" data-slide="prev">
      <span class="glyphicon glyphicon-chevron-left"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="right carousel-control" href="#myCarousel" data-slide="next">
      <span class="glyphicon glyphicon-chevron-right"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

</body>
</html>
 
