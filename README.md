<!DOCTYPE html>
<html>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="/w3css/3/w3.css">
<body>

<!-- Navigation -->
<nav class="w3-bar w3-black">
  <a href="#home" class="w3-button w3-bar-item">Home</a>
  <a href="#band" class="w3-button w3-bar-item">Band</a>
  <a href="#tour" class="w3-button w3-bar-item">Tour</a>
  <a href="#contact" class="w3-button w3-bar-item">Contact</a>
</nav>

<!-- Slide Show Legg til bilde -->
<section>
  <img class="mySlides" src="HER"
  style="width:100%">
  <img class="mySlides" src="HER"
  style="width:100%">
  <img class="mySlides" src="HER"
  style="width:100%">
</section>

<script>
// Automatic Slideshow - change image every 3 seconds OBS! JavaScript nedover
var myIndex = 0;
carousel();

function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
    for (i = 0; i < x.length; i++) {
       x[i].style.display = "none";
    }
    myIndex++;
    if (myIndex > x.length) {myIndex = 1}
    x[myIndex-1].style.display = "block";
    setTimeout(carousel, 3000);
}
</script>

</body>
</html>

