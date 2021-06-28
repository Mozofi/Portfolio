---
title: Examples
layout: template
filename: Examples.md
--- 

<!DOCTYPE html>
<html lang="en">
<meta charset="UTF-8">
<b><title>Mozofi's Portfolio website</title>
<meta name="viewport" content="width=device-width,initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
  
<style>
  body {
    background-image: url('ThunderK.jpg');
    background-repeat: no-repeat;
    background-attachment: fixed;
    background-size: cover;
  }
</style>
  
<script src=""></script>
  
<body style="background-color:null;">
  <center><b>
    <h1>My Portfolio 2</h1>
      <p><em>These are some example images.</em></p>
      </b>
    
    <!-- Side navigation -->
<div class="sidenav">
  <a href="Mozofi.github.io/Portfolio/">Home</a><br>
  <a href="Mozofi.github.io/Examples/">Example Apps</a><br>
  <a href="#">Contact</a><br>
</div>
    
    <p>Table table</p>  
  
    <table>
  <tr>
    <th>Lightning</th>
    <th>Chameleon</th>
    <th>Lil Clown</th>
  </tr>
  <tr>
    <td>  <img src="LightningK.jpg" alt="Lightning" style="width="500" height="500">  </td>
    <td>  <img src="ChameleonN.jpg" alt="Chameleon" style="width="500" height="500"> </td>
    <td>  <img src="ClownJ.jpg" alt="Clown" style="width="500" height="500">  </td>
  </tr>
</table>                                                                                                                                                       

   
<br><br>
      
<button id="button1" style="background-color:Cyan; border-color:Black; color:Black" onclick="button1press()">Cyan</button>
<button id="button2" style="background-color:Red; border-color:Black; color:Black" onclick="button2press()">Red</button>                                            
<button id="button3" style="background-color:DarkGreen; border-color:Black; color:Black" onclick="button3press()">Green</button>
<button id="button4" style="background-image: url('Thunder.jpg'); border-color:Black; color:Black" onclick="button4press()">Thunder</button>

      <p id="demo"></p>                                                  
<script>
function button1press() {
  document.getElementById("demo").innerHTML = "Color changed to " + "Cyan";
  document.body.style.backgroundImage = 'none';
  document.body.style.backgroundColor = "Aquamarine";
}
function button2press() {
  document.getElementById("demo").innerHTML = "Color changed to " + "Red";
  document.body.style.backgroundImage = 'none';
  document.body.style.backgroundColor = "Tomato";
}
function button3press() {
  document.getElementById("demo").innerHTML = "Color changed to " + "Green";
  document.body.style.backgroundImage = 'none';
  document.body.style.backgroundColor = "ForestGreen";
}
function button4press() {
  document.getElementById("demo").innerHTML = "Image changed to " + "Thunder";
  document.body.style.backgroundImage = "url('ThunderK.jpg')";
}                                                                      
</script>                                                                                              

<a href="https://mozofi.github.io/Portfolio/"><s>Refresh the page for now!</s></a>
      
</center>
</body>
</html>
