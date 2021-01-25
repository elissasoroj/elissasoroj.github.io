
<p style="text-align: center;">
<img src="photos/elissa1.jpg" alt="Trying to color-coordinate with the plants since 2015" width="400"/><br><br>

## Hi! My name is Elissa
</p>

---

I am a joint PhD student at E3B Columbia and the graduate studies program at NYBG. 
I'm interested in studying the evolution of morphological diversity in various strange and wonderful plant groups, including:

<p style="text-align: center;">

 *Pedicularis*

 <img src="photos/pedicularis_diversity.png" alt="Pedicularis flowers" width="300"/><br><br>

Ferns

<img src="photos/ferns.jpg" alt="ferns" width="300"/><br><br>

and Lycophytes 

<img src="photos/lyco_diversity.png" alt="lycophyte fruits" width="300"/><br><br>
</p>

---

## BC (Before Columbia)

I worked at the Yale Peabody Museum of Natural History, where my affinity for dead things served me well...

<img src="photos/elissa2.jpg" alt="Picking up dead things since my Mom couldn't tell me not to" width="300"/><br>
</p>

At YPM I managed digitization activities for the Western Interior Seaway NSF TCN Grant. The goal of the grant was to digitize and photograph all the fossil specimens from the Western Interior Seaway in YPM's collection.



 ~

Prior to working at YPM I earned my undergraduate degree from Brown University where I studied bat wing morphology in the [Aeromechanics and Evolutionary Morphology Lab](https://www.brown.edu/Departments/EEB/EML/). For my indepedent research I used histology to characterize the morphology of the trailing edge, but I also had the great pleasure of training bats to fly through tiny windows 


---

## Illustration

I'm  also a scientific illustrator and I love to nerd out about science communication

<div class="row">
  <div class="column">
    <img src="photos/illustration/octo.png">
    <img src="photos/illustration/horseshoe.jpg">
    <img src="photos/illustration/B_carterae.png">
    <img src="photos/illustration/batheads.png">
    <img src="photos/illustration/pitcher.png">
  </div>
  <div class="column">
    <img src="photos/illustration/biochem.jpg">
    <img src="photos/illustration/engn_figs.jpg">
    <img src="photos/illustration/darker.jpg">
    <img src="photos/illustration/mosquito.png">
    <img src="photos/illustration/spinalcord.jpg">
  </div>
  <div class="column">
    <img src="photos/illustration/horseshoecrab_ink.png">
    <img src="photos/illustration/flicker.jpg">
  </div>
</div>

<style>
.row {
  display: flex;
  flex-wrap: wrap;
  padding: 0 4px;
}

/* Create two equal columns that sits next to each other */
.column {
  flex: 50%;
  padding: 0 4px;
}

.column img {
  margin-top: 8px;
  vertical-align: middle;
}
</style>

<button onclick="one()">1</button>
<button onclick="two()">2</button>
<button onclick="three()">3</button>

<script>
// Get the elements with class="column"
var elements = document.getElementsByClassName("column");

// Declare a "loop" variable
var i;

// Full-width images
function one() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.flex = "100%";
  }
}

// Two images side by side
function two() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.flex = "50%";
  }
}

// Four images side by side
function three() {
  for (i = 0; i < elements.length; i++) {
    elements[i].style.flex = "33%";
  }
}
</script>