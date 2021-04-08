<!DOCTYPE html>

<html>






<style>

#whiteBox {
  width: 900px;
  height: 650px ;
  background-color: white;
  position: absolute;
  
  right: 25px;
  top: 15%;
}
body {
    background-image: url('Space.jpg');
    background-repeat: no-repeat;
    background-size: 100% 100%;
    
        
      }


h6 {      font-size: 200%;     } 
h1 {      font-size: 300%;     } 
</style>


<h1 style="color:rgb(236, 236, 236); border:2px solid rgb(255, 255, 255);"><center> Our Solar System </center></h1>


<html>
<head>
<style>
ul {
  list-style-type: none;
  margin: 0;
  padding: 0;
  overflow: hidden;
  background-color: #333;
}

li {
  float: left;
  border-right:1px solid #bbb;
}

li:last-child {
  border-right: none;
}

li a {
  display: block;
  color: white;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

li a:hover:not(.active) {
  background-color: #111;
}

.active {
  background-color: #3140c4;
}
</style>
</head>
<body>

<ul>
  <li><a class="active" href="#home">Home</a></li>
  <li><a href="C:\Users\shara\Downloads\Coding\Solar_System\Mercury.html">Mercury</a></li>
  <li><a href="#contact">Contact</a></li>
  <li style="float:right"><a href="#about">About</a></li>
</ul>

</body> 


<h2 style="color:rgb(255, 255, 255);"><center>The Solar System is the gravitationally bound system of the Sun and the objects that orbit it, either directly or indirectly. Of the objects that orbit the Sun directly, the largest are the eight planets, with the remainder being smaller objects, the dwarf planets and small Solar System bodies. </center> </h2>

<h6 style="color:rgb(255, 255, 255);"><center> Inner Solar System</center></h6>
<h3 style="color:rgb(255, 255, 255);"><center>The inner planets (in order of distance from the sun, closest to furthest) are Mercury, Venus, Earth and Mars.The inner planets are closer to the Sun and are smaller and rockier.The four inner planets are called terrestrial planets because their surfaces are solid (and, as the name implies, somewhat similar to Earth — although the term can be misleading because each of the four has vastly different environments). They’re made up mostly of heavy metals such as iron and nickel, and have either no moons or few moons. </center></h3>

<h6 style="color:rgb(255, 255, 255);"><center>Outer Solar System</center></h6>
<h3 style="color:rgb(255, 255, 255);"><center>The outer planets (sometimes called Jovian planets or gas giants) are huge planets swaddled in gas. They all have rings and all of plenty of moons each.The outer planets are gas giants Jupiter and Saturn and ice giants Uranus and Neptune.</center> </h3>

<script>
  function light(sw) {
    var pic;
    
    if (sw == 0) {
      pic = "Outer.jpg"
    } else {
      pic = "inner.jpg"
        } 
    if (sw == 2) {
      pic = "Whole.png"
    }
    document.getElementById('Whole.png').src = pic;
  }
  </script>
  
  <center><img id="Whole.png" src="Whole.png" width="700" height="400"></center>
  
  <p>
    <center><button type="button" onclick="light(1)">Inner planets</button></center>
    <center><button type="button" onclick="light(0)">Outer Planner</button></center>
    <center><button type="button" onclick="light(2)">Whole</button></center>
  </p>
