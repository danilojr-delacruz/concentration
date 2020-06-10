# Concentration Phenomena in Asymptotic Geometry
A collection of code and visualisations related to the MATH40008 Poster Project on Concentration of Volume. 

<details>
<summary><b>What is MATH40008?</b></summary>
<br>
  <p align="justify">
  MATH40008 is a module all first year maths undergraduates at Imperial College London take after completing their summer exams. They are expected to construct a poster and give a presentation on a topic related to one of the five main topics provided by the department via independent research. Concentration of Volume falls under 'Law of Large Numbers and The Central Limit Theorem'.
    <hr>
</p>

</details>

<p align="justify">
One of the main theorems we showcase in the poster is that in high dimensions almost all the volume of the <img src="https://latex.codecogs.com/gif.latex?n-\mathrm{Cube}"> concentrates on an <img src="https://latex.codecogs.com/gif.latex?(n-1)-\mathrm{Sphere}">. Formally we want to show that

<p align="center">
  <img src="https://latex.codecogs.com/gif.latex?\forall&space;\varepsilon&space;>&space;0,&space;\,&space;\mathrm{Vol}\left(&space;U_{n,\varepsilon}\cap[-1,1]^n\right)\rightarrow&space;\mathrm{Vol}([-1,1]^n)">
  <br>
  <img src="https://latex.codecogs.com/gif.latex?U_{n,\varepsilon}&space;:=&space;\left\{x:&space;(1-\varepsilon)\sqrt{n/3}<\|x\|<(1&plus;\varepsilon)\sqrt{n/3}\right\}"> 
  
</p>
 
The main idea is that in high dimensional cubes we can think of a point's coordinates as independent and identically distributed (i.i.d) random variables. In order for a point to lie at an extremity these random variables must all cooperate in the same direction. This is unlikely and the Law of Large Number stipulates that for large n this is impossible. Instead, the collective effort of these random variables will reflect their average. Geometrically speaking, this means points must exist a certain distance from the origin (a sphere in high dimensions). For more details see the poster and the proofs folder in this repository.
</p>


<p align="center">
  <img width="600" height="300" src=figures/hypercube_conc_hist.gif>
  <br></br>
  <caption><b>Figure 1</b> - For higher dimensions we can see that more and more of the volume of the cube falls inside the sphere.</caption>
</p>

<p align="center">
  <img width="600" height="300" src=figures/rate_conc_graph.png>
  <br></br>
  <caption><b>Figure 2</b> - The concentration eventually increases to 1 no matter how slow. <br> In other words, the sphere contains almost all the volume of the cube. </caption>
</p>
