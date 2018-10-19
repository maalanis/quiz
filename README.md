<!DOCTYPE html>
<html>
<head>
<title >What RockStar best fits your personality?</title>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>
<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>
</head>

<body>

<div id="main">
<div id="header">
<h1 style="color:black; font-weight: bold;">Which Rockstar fits your personality?</h1>
</div>


<form id="form1">
<div id="carouselExampleControls" id="myCarousel" class="carousel slide" data-ride="false">
  <div id ="car-text" class="carousel-inner">
    <div class="carousel-item active">
   <h2 id="fade">You head to a music store what's the first thing you buy?</h2>

   <div id="background-button">
   <button type="button" id="buttonx" class="btn btn-danger"><label for="var_info"><input type="radio"name="variable" value="1" id="var_info">Guitar</label></button>
  <!--<label id="m" for="var_string"><input type="radio" name="variable" value="2" id="var_string" />Microphone</label>-->
  <!--<label for="var_join"><input type="button" class="btn btn-outline-danger" name="variable" value="3" id="var_join" />Guitars and Basses.</label>-->
   <button type="button" id="buttonx" class="btn btn-warning"><label for="var_info2"><input type="radio"name="variable" value="2" id="var_info2">Drums</label></button>
  <button type="button" id="buttonx"class="btn btn-success"><label for="var_info3"><input type="radio" name="variable" value="3" id="var_info3" />Keyboard</label></button>
  <button type="button"id="buttonx"class="btn btn-danger"><label for="var_condition"><input type="radio" name="variable" value="6" id="var_condition"/>Computer Equipment.</label></button>
</div>
      <img class="d-block w-100" src="store.jpg" alt="First slide">
    </div>
    <div class="carousel-item">
  <h2>What is your favorite place to watch live music?</h2>
  <div>
     <div id="background-button">
<button type="button" id="buttonx"class="btn btn-danger"><label for="cat_string"><input type="radio" name="con" value="0" id="cat_string" />Coffee Shop</label></button>
<button type="button" id="buttonx"class="btn btn-warning"><label for="cat_join"><input type="radio" name="con" value="0" id="cat_join" />Outdoor Venue</label></button>
<button type="button" id="buttonx"class="btn btn-success"><label for="cat_info1"><input type="radio" name="con" value="0" id="cat_info1" />Stadium</label></button>
<button type="button" id="buttonx"class="btn btn-danger"><label for="cat_info2"><input type="radio" name="con" value="0" id="cat_info2" />Bar</label></button>
<button type="button" id="buttonx"class="btn btn-success"><label for="cat_condition"><input type="radio" name="con" value="" id="cat_condition" />House Party</label></button>
</div>
      <img class="d-block w-100" src="houseparty.jpg" alt="Second slide">
    </div>
    </div>
    <div class="carousel-item">
    <h2>Who are you in the band?</h2>
     <div id="background-button">
<button type="button" id="buttonx"class="btn btn-danger"><label for="cat_join4"><input type="radio" name="con2" value="0" id="cat_join4" />The Leader</label></button>
<button type="button" id="buttonx"class="btn btn-warning"><label for="cat_info5"><input type="radio" name="con2" value="0" id="cat_info5" />instrument guru</label></button>
<button type="button"id="buttonx" class="btn btn-success"><label for="cat_info6"><input type="radio" name="con2" value="0" id="cat_info6" />Mysterious</label></button>
<button type="button" id="buttonx"class="btn btn-danger"><label for="cat_info7"><input type="radio" name="con2" value="0" id="cat_info7" />Eccentric</label></button>
</div>
      <img class="d-block w-100" src="freedie.jpg" alt="Third slide">
    </div>
  <div class="carousel-item">
    <h2>What is your favorite part of the music process?</h2>
     <div id="background-button">
<button type="button" id="buttonx" class="btn btn-danger"><label for="if_string"><input type="radio" name="ifstate" value="0" id="if_string" />Playing Shows</label></button>
<button type="button" id="buttonx" class="btn btn-warning"><label for="if_join"><input type="radio" name="ifstate" value="0" id="if_join" />Recording Music</label></button>
<button type="button" id="buttonx" class="btn btn-success"><label for="if_info1"><input type="radio" name="ifstate" value="0" id="if_info1" />Jamming (Writing Music)</label></button>
<button type="button" id="buttonx" class="btn btn-danger"><label for="if_condition"><input type="radio" name="ifstate"  value="0" id="if_condition" />Partying Balls</label></button>
</div>
      <img class="d-block w-100" src="sixties.jpg" alt="Fourth slide">
    </div>
    </form>
     <div class="carousel-item">
        <button type="submit" value="Submit" onclick="function()">Submit</button> 
        <div>
        <p>Your grade is: <span id="grade">__</span></p>
        <p id="grade2"></p>
    </div>
        </div>
        
  </div>

  <a id="leftButton" class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev" >
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a id="rightButton" class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

</div><!-- close main div -->


<script>
document.getElementById("form1").onsubmit=function() {
   variable = parseInt(document.querySelector('input[name = "variable"]:checked').value);
     con = parseInt(document.querySelector('input[name = "con"]:checked').value);
     con2 = parseInt(document.querySelector('input[name = "con2"]:checked').value);
     ifstate = parseInt(document.querySelector('input[name = "ifstate"]:checked').value);
     
     
     result = variable + con + con2 + ifstate;
     
  document.getElementById("grade").innerHTML = result;
 if (result =6) {result2 = "Jim Morrison The sexy American Poet.<br /><img src='jim-morrison2.gif' width='300' />"};
    if (result ==7) {result2 = "Flea the wild bassist of the Red Hot Chili Peppers.<br /><img src='poor.jpg' width='300' />"};
    if (result== 8) {result2 = "Jimi Hendrix the guitar legend who excited and charmed everyone around him.<br /><img src='avg.jpg' width='300' />"};
    if (result ==9) {result2 = "Axl Rose the rebellious romantic who captivated the 80's with his Wild voice and attitude.<br /><img src='above.jpg' width='300' />"};
    if (result ==10) {result2 = "Slash the wild Guitarist from Guns N Roses who listened to no one and partied like there was no tomorrow and captivated the world with Legendary solos<br /><img src='excellent.jpg' width='300' />"};
  if (result == 11) {result2 = "You're a JavaScript pro!<br /><img src='excellent.jpg' width='300' />"};
  if (result == 100) {result2 = "You're a JavaScript pro!<br /><img src='excellent.jpg' width='300' />"};
  

document.getElementById("grade2").innerHTML = result2; 
//document.getElementById("grade2").
     

//$("#div1").fadeOut();
return false; // required to not refresh the page; just leave this here
} //this ends the submit function

</script>

</body>

</html>

<style>
body {
background-image: url("wallpaper2.jpg");
background-color: darkred;
font-family: "Times New Roman", Times, serif;
}
label{
  font-size: 27px;
}
#main {
width: 80%;
max-width: 950px;
border: 1px gray solid;
margin: auto;
padding: 10px;
background-color: white;
border-radius: 10px;
}
#buttonx{
  margin-left: 1%;
  margin-bottom: 1%;
  margin-top: 2%;
}
#buttonx:active {
    background-color: yellow;
  }
#car-text{
  text-align: center;

    padding-left: 100px;
    padding-right: 100px;
}
#leftButton{
  background-color: #6502d6;
  opacity: 1;
 
  border-style: groove;
  height: 200px;
  margin-top: 4.95%;
  width: 100px;
  border-color:black;
}
#rightButton{
  background-color: #6502d6;
  opacity: 1;


  border-style: groove;
   margin-top: 4.95%;
    height: 200px;
     width: 100px;
     border-color: black;
     }
#container{
  height: 200px;
}

#background-button{
  background-color: black;
  height: 200px;
  margin-bottom: 5%;

}
#header {
margin-top: 0;
font-family: "Courier New", Courier, "Lucida Sans Typewriter", "Lucida Typewriter", monospace;
font-weight: bold;
border: 2px solid black;
padding: 5px;
padding-left: 90px;
margin-left: 200px;
width: 500px;
height: 190px;
background: beige;
background-image: url("woodstockjimi.gif");
color: white;
}
</style>
