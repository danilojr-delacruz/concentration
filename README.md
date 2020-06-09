# Concentration of Volume
A collection of code and visualisation related to the MATH40008 Poster Project on Concentration of Volume. 

MATH40008 is a module all first year maths undergraduates at Imperial College London take after completing their summer exams. They are expected to construct a poster and give a presentation on a topic related to one of the five main topics provided by the department via independent research. Concentration of Volume falls under 'Law of Large Number and The Central Limit Theorem' and we will see how they play a role in proving the asymptotic concentration of volume in hypercubes.

One of the main theorems we showcase in the poster is that in high dimensions almost all the volume of the $n$-Cube concentrates on the $(n-1)$ sphere. Formally we want to show that:

**Theorem** - 
\forall \varepsilon > 0, \, \mathrm{Vol}\left( U_{n,\varepsilon}\cap[-1,1]^n\right)\rightarrow \mathrm{Vol}([-1,1]^n)\]\[
U_{n,\varepsilon} := \left\{x: (1-\varepsilon)\sqrt{n/3}<\|x\|<(1+\varepsilon)\sqrt{n/3}\right\}$$

<p align="center">
  <img width="600" height="300" src=hypercube_conc_hist.gif>
  <caption></caption>
</p>

<p align="center">
  <img width="600" height="300" src=rate_conc_graph.png>
</p>
