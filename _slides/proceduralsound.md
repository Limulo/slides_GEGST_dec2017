# Procedural Sound in VideoGames


<!-- .slide: data-background-color="#fff" -->
<!-- modello data driven -->
<!--
<svg width="40%" viewBox="0 0 206.7433 323.99786">

  <svg class="fragment" data-fragment-index="3">
    <use xlink:href="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/graphics/data-driven.svg#database">
  </svg>

  <svg class="fragment" data-fragment-index="2">
    <use xlink:href="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/graphics/data-driven.svg#arrow">
  </svg>

  <svg data-fragment-index="1">
    <use xlink:href="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/graphics/data-driven.svg#wavefiles">
  </svg>

</svg>
-->
<svg width="40%" viewBox="0 0 206.7433 323.99786">

  <svg class="fragment" data-fragment-index="3">
    <use xlink:href="/images/pt3/data-driven.svg#database">
  </svg>

  <svg class="fragment" data-fragment-index="2">
    <use xlink:href="/images/pt3/data-driven.svg#arrow">
  </svg>

  <svg data-fragment-index="1">
    <use xlink:href="/images/pt3/data-driven.svg#wavefiles">
  </svg>

</svg>


<!-- .slide: data-background-color="#11a0dc" data-background-size="contain" data-background-image="images/pt3/jaws.jpg" -->
<!-- jaws arcade advertise -->


<!-- .slide: data-background-color="#fff" data-background-size="contain" data-background-image="images/pt3/MT_32.jpg" -->
<!-- roland MT-32 -->


<!-- .slide: data-background-color="#fff" data-background-size="contain" data-background-image="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-05/pt2/tetrahedron.png" -->
<!-- tetrahedron -->


<iframe width="100%" height="500px" src="https://sketchfab.com/models/d6c802a74a174c8c805deb20186d1877/embed" frameborder="0" allowvr allowfullscreen mozallowfullscreen="true" webkitallowfullscreen="true" onmousewheel="">
</iframe>
<!-- grafica per realismo -->


<!-- .slide: data-background-color="#fff" data-background-size="contain" data-background-image="images/pt3/diapo-uv-map.png" -->
<!-- uv mapping -->


<!-- .slide: data-background-color="#000" data-background-size="contain" data-background-image="images/pt3/diapo-crash.png" -->
<!-- crash bandicoot -->


<!-- .slide: data-background-color="#000" data-background-size="contain" data-background-image="images/pt3/toy-story-1.jpg" -->
<!-- toy story -->


<!-- .slide: data-background-color="#fff" -->
<!-- fotografie -->
<svg width="110%" viewBox="0 0 885.86365 343.30991">

  <svg class="fragment" data-fragment-index="2">
    <use xlink:href="images/pt3/diapo-foto.svg#modifications">
  </svg>

  <svg data-fragment-index="1">
    <use xlink:href="images/pt3/diapo-foto.svg#main">
  </svg>

</svg>


<!-- .slide: data-background-color="#000" data-background-size="contain" data-background-image="images/pt3/david2.jpg" -->



## Sound as a process
niente trucchi da 4 soldi<!-- .element: class="fragment" -->


<!-- .slide: data-background-color="#fff" -->
![door](https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/esempi-procedurale/open-door.png)


<!-- .slide: data-background-color="#fff" -->
![steel plate](https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/esempi-procedurale/steel-plate.png)



## virtual analog


<!-- .slide: data-background-color="#fff" data-background-size="contain" data-background-image="images/pt3/diapo-virtual-analog.png" -->



## physical modelling


<!-- .slide: data-background-color="#fff" -->
| ![Pianoteq](https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-09/pt3/pianoteq.png) | <iframe width="100%" height="315" src="https://www.youtube.com/embed/djUseuUisvM" frameborder="0" allowfullscreen></iframe> | ![Arturia B3](https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-05/pt2/Arturia-B3V.png) |
|:-:|:-:|:-:|
| ![Antares Throat](https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-05/pt2/Antares_Throat.jpg) | ![Aeolus](https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-12/pt3/Aeolus.png) | ![Melodyne](https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-05/pt2/Melodyne.jpg) |


<table>
<tr>
<td>
<img src="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-09/pt3/ravenscroft.jpg" />
</td>
<td>
<img src="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-09/pt3/pianoteq.png" />
</td>
</tr>
</table>


| name | [ravencroft](https://www.vilabsaudio.com/Ravenscroft-By-VI-Labs) | [pianoteq](https://www.pianoteq.com/) |
|--:|:-:|:-:|
| company | VI Labs | Moddartt |
| samples | 17000 | 0 |
| disk space req. | 5.32 GB | 40 GB |
| ram | 4 GB | 256 MB |


<!-- .slide: data-background-color="#fff" -->
![comparison](https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-09/pt3/40MB-v-5.32GB.png)



## Procedural audio


>Procedural audio is non-linear, often synthetic sound, created in real time according to a set of programmatic rules and live input.<br/><br/><span style="font-size:0.7em;">from "[An introduction to procedural audio and its application in computer games](http://cs.au.dk/~dsound/DigitalAudio.dir/Papers/proceduralAudio.pdf)"<br/>by Andy Farnell</span>


<!-- .slide: data-background-color="#fff" -->
<table style="width:100%;">
<tr>
<td>
<img class="fragment fade-right" src="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-05/pt2/book-Perry-Cook.png" alt="Perry Cook's book" width="100%;" />
</td>
<td>
<img class="fragment fade-left" src="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-05/pt2/book-designing-sounds.jpg" alt="Andy Farnell's book" width="100%;" />
</td>
</tr>
</table>



## some examples



<!-- .slide: data-background-color="#fff" data-background-size="contain" data-background-image="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/graphics/beh-mod-impl.png" -->


<!-- .slide: data-background-color="#fff" data-background-size="contain" data-background-image="images/pt3/vectrorial_vs_raster.png" -->



## vantaggi


differimento


variabilità


<!-- .slide: data-background-color="#fff" -->
default forms

![default form](https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/graphics/collision.png)


<!-- .slide: data-background-color="#fff" -->
LOAD

![L.O.A.D.](https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-05/pt2/mipmap.jpg)



## svantaggi

industrial inertia<!-- .element: class="fragment"-->

new skills<!-- .element: class="fragment"-->

sintesi = falso (!!)<!-- .element: class="fragment"-->


<!-- .slide: data-background-color="#fff" -->
![PIM](https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/graphics/physically-inpired-model-bis.png)



<!-- .slide: data-background-color="#fff" data-background-size="contain" data-background-image="images/pt3/diapo-aristotele.png" -->
<!-- Aristotele + Chion -->



## the future


As in computer graphics (rigging, textures, animation, modelling, light, visual fxs) <span class="fragment">so in sound design ([fracture sound](http://www.cs.cornell.edu/projects/FractureSound/), [friction](http://independent.academia.edu/StefaniaSerafin), water and [bubbles](http://www.cs.cornell.edu/projects/Sound/bubbles/), [crumpling](http://www.cs.columbia.edu/cg/crumpling/), fire, [impacts](http://www.cs.ubc.ca/~kvdoel/publications/modalpaper.pdf), [environmental acoustics](http://www.ness-music.eu/wp-content/uploads/2013/04/TASL2256897.pdf))</span>


<!-- .slide: data-background-color="#fff" data-background-size="contain" data-background-image="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-09/pt3/sierra-lipsync.jpg" -->
<!-- animation driven by audio -->


<!-- .slide: data-background-color="#000" data-background-size="contain" data-background-image="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images//2017-09/pt3/Ghost-Recon.png" -->
<!-- animation driven by audio -->


![inverse fooley](images/pt3/inverse-fooley.png)


<iframe width="100%" height="500" src="https://www.youtube.com/embed/EGkQkdCKztM?start=130" frameborder="0" allowfullscreen></iframe>


<iframe width="100%" height="500" src="https://www.youtube.com/embed/EGkQkdCKztM?start=226" frameborder="0" allowfullscreen></iframe>




## Godot & PureData


<!-- .slide: data-background-color="#fff" data-background-size="contain" data-background-image="https://raw.githubusercontent.com/Limulo/game-sound-sae2017/master/images/2017-09/pt3/godot/Pd-Player.png" -->
