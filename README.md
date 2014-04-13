rods bending
============

This package is able to calculate the shape of thin flexible elastic rod under load.

It can handle large loads and nonlinear deformations of rod.

It was developed to describe the shape of microtubules bending
under the force of kinesins in this paper:   
Doodhi H, Katrukha EA, Kapitein LC, Akhmanova A. [Mechanical and geometrical constraints control kinesin-based microtubule guidance.](http://www.ncbi.nlm.nih.gov/pubmed/24462000) Curr Biol. 2014 Feb 3;24(3):322-8.  


<img src="http://katpyxa.info/software/rods_bending/rods_bending.gif"/> 

In supplemental material you can find quite detailed description of theory and numerical realization behind it.  
But actually it is pretty general and can be applied to any other thin rod (macroscopic too).

Main parameters that you need to know are:   
- length of the rod  
- its flexural rigidity  
- magnitude of force applied to one end (the other one is clamped)  
- direction of the force  

Theory behind it is described in "[Theory of Elasticity](https://archive.org/details/TheoryOfElasticity)" by L.D. Landau & E.M. Lifshitz (see Chapter 2), but it is very compressed and hard to read explanation.

If you want to know more about banding rods (different clamping, following force, etc), I would recommend to read the book of E.V. Popov "Theory and calculation of flexible elastic rods", but it is available only [in Russian](http://katpyxa.info/software/rods_bending/Popov%20E.V.%20Teoriya%20i%20raschet%20gibkih%20uprugih%20sterzhnej%20(Nauka,%201986)(ru)(K)(600dpi)(T)(296s)_PCem_.djvu).

<img src="http://katpyxa.info/software/rods_bending/popov.png" align="right" />
<br />
<br />
<br />
<br />
<br />
Developed in <a href='http://www.cellbiology.nl/'>Cell Biology group</a> of Utrecht University.  
Write an e-mail <a href="mailto:y.katrukha@uu.nl">for any questions</a>.
