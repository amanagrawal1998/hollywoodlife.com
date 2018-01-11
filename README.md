# hollywoodlife.com
A webpage which gives you some of the updates regarding what is going on in hollywood.The code is written in html, css and javascript.
<html>
<head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
.menu
{
overflow:hidden;
background-color:black;
}
.menu a
{
float:right;
color:white;
text-align:center;
padding:15px 15px;
text-decoration:none;
font-size:24px;
}
.menu a:hover
{
background-color:#ddd;
color:black;
}
body
{
background: -webkit-linear-gradient(left, black, white);
}
.x a{font-family:"Brush Script MT", Brush Script Std, cursive;
font-size:60px;
color:lightblue;
font-style:none;}
.slideshow-container {
  max-width: 1000px;
  position: relative;
  margin: auto;
}

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
}
.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}
.prev:hover, .next:hover {
  background-color: rgba(0,0,0,0.8);
}
.text {
  color: black;
  font-size: 40px;
  padding: 8px 12px;
  position: absolute;
  bottom: 8px;
  width: 100%;
  text-align: center;
}
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}
@media only screen and (max-width: 300px) {
  .prev, .next,.text {font-size: 11px}
}
.style{border:4px black solid}
#i{
float:right;
font-size:48px;
}
.border
{
border:2px solid white;
-webkit-animation-fill-mode: both; 
    animation-name: example;
    animation-duration: 5s;
	margin:0 60px 0 60px;
}
@keyframes example {
    from {width:0%;}
    to {width:100%;}
}
.footer
{
background-color:black;
text-align:center;
}
</style>
<body>
<header class="x">
<a href>Hollywood Life</a>
<a href="https://www.facebook.com/HollywoodLife"><i id="i" class="fa fa-facebook-official" aria-hidden="true" style="color:blue"></i></a>
<a href="https://twitter.com/HollywoodLife?ref_src=twsrc%5Egoogle%7Ctwcamp%5Eserp%7Ctwgr%5Eauthor"><i id="i" class="fa fa-twitter" aria-hidden="true" style="color:lightblue;margin:0 10px 0 0"></i></a>
<a href="https://www.instagram.com/hollywoodlife/?hl=en"><i id="i" class="fa fa-instagram" aria-hidden="true" style="color:purple;margin:0 10px 0 0"></i></a>
</header>
<div class="menu">
<a href="#about">About</a>
<a href="#contact">Contact</a>
<a href="https://www.usmagazine.com/celebrity-news/" target="_blank">News</a>
<a href="#songs">Songs</a>
<a href="#despacito">Videos</a>
<a id="#home" href>Home</a>
</div>
<br>
<br>
<div class="slideshow-container">

<div class="mySlides">
  <div class="numbertext">1 / 4</div>
  <a href="https://www.billboard.com/articles/columns/pop/8070393/taylor-swift-reputation-tour-trailer-video" target="_blank">
  <img src="reputation.jpg" style="width:100%;height:500px;"></a>
  <br><br><br><br><br>
  <div class="text" style="font-family:'Brush Script MT', Brush Script Std, cursive;">Reputation is Out</div>
</div>

<div class="mySlides">
  <div class="numbertext">2 / 4</div>
  <a href="https://www.billboard.com/articles/columns/pop/7710111/ed-sheeran-divide-album-songs-superlatives" target="_blank">
  <img src="ed.jpg" style="width:100%;height:550px;">
  </a>
  <br><br><br><br><br>
  <div class="text" style="font-family:'Brush Script MT', Brush Script Std, cursive;">Full divide album</div>
</div>

<div class="mySlides">
  <div class="numbertext">3 / 4</div>
  <a href="https://www.nbcnews.com/news/nbcblk/pepsi-ad-kendall-jenner-echoes-black-lives-matter-sparks-anger-n742811" target="_blank">
  <img src="controversy.jpg" style="width:100%;height:500px">
  </a>
  <br><br><br><br><br>
  <div class="text"style="font-family:'Brush Script MT', Brush Script Std, cursive;">Kendal's Controversy</div>
</div>
<div class="mySlides">
  <div class="numbertext">4 / 4</div>
  <img src="the-best.jpeg" style="width:100%;height:550px;">
</div>

<a class="prev" onclick="plusSlides(-1)">&#10094;</a>
<a class="next" onclick="plusSlides(1)">&#10095;</a>

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
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  slides[slideIndex-1].style.display = "block";  
}
</script>
<br>
<br><br><br>
<div id="about" style="color:white;font-size:30px;font-family:'Brush Script MT', Brush Script Std, cursive;" class="style">
This is a website which makes you to get all the info about your favourite superstars,singers,actors ,sports personality etc.<br>
Special features:
<ul>
<li>Download Your favourite Songs.</li>
<li>Watch online videos.</li>
<li>Frequently updated with the news.</li>
<li>Get notified all the time.</li>
<li>Cheap subscription offers.</li>
<li>And lots more</li>
</ul>
</div>
<br>
<br>
<br>
<p style="color:white;font-size:60px;font-family:'Brush Script MT', Brush Script Std, cursive;margin:50 0 0 60px">Watch the latest videos</p>
<div class="border"></div>
<iframe id="despacito" width="560" height="315" src="https://www.youtube-nocookie.com/embed/kJQP7kiw5Fk?" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen style="margin:60px 60px 0 60px"></iframe>
<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/2Vv-BfVoq4g" frameborder="0" gesture="media" allow="encrypted-media" allowfullscreen></iframe>
<br><br>
<p style="color:white;font-size:60px;font-family:'Brush Script MT', Brush Script Std, cursive;margin:50 0 0 60px">Listen to our Music</p>
<div class="border"></div>
<iframe src="https://open.spotify.com/embed/track/0tgVpDi06FyKpA1z0VMD4v"
              width="300" height="300" frameborder="0" allowtransparency="true" style="margin:60px" id="songs"></iframe>
<iframe src="https://open.spotify.com/embed/track/6PJ8FF6UR8FZXfEvpHkIVN"
              width="300" height="300" frameborder="0" allowtransparency="true"style="margin:60px"></iframe>			  
<iframe src="https://open.spotify.com/embed/track/35QZaWQRkmnAVqBF1TLCxQ"
              width="300" height="300" frameborder="0" allowtransparency="true" style="margin:60px"></iframe>
<iframe src="https://open.spotify.com/embed/track/0afhq8XCExXpqazXczTSve"
              width="300" height="300" frameborder="0" allowtransparency="true" style="margin:60px"></iframe>
			  <iframe src="https://open.spotify.com/embed/track/2RttW7RAu5nOAfq6YFvApB"
              width="300" height="300" frameborder="0" allowtransparency="true" style="margin:60px"></iframe>
			  <iframe src="https://open.spotify.com/embed/track/7qiZfU4dY1lWllzX7mPBI3"
              width="300" height="300" frameborder="0" allowtransparency="true"style="margin:60px"></iframe>
			  <p style="color:white;font-size:60px;font-family:'Brush Script MT', Brush Script Std, cursive;margin:50 0 0 60px;text-align:center">And much more...</p>
<div class="footer">
<br>
<br>
<a href="#home" style="font-family:'Brush Script MT', Brush Script Std, cursive;font-size:42px;
color:lightblue;
font-style:none;
">Hollywood Life</a>
<p style="color:white;margin:10px">Music</p> 
<p style="color:white;margin:10px">Video</p>  
<p style="color:white;margin:10px">News</p> 
<p style="color:white;margin:10px">Fun</p>        
<p style="color:white;margin:10px">And lots more</p>
<p style="color:white;margin:10px;font-size:20px" id="contact">Contact us:9087773714,8577879639 or mail us at hllife@gmail.com</p>
<br>
<br>
</div>
</body>
</head>
</html>
