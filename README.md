# Ansys Homerwork

Collection of all exercize develop in APDL in Ansys

<ul>
	<li>exercize n. 1</li> 
	<li>exercize n. 2</li>
		<ul> 
 			<li>section 1</li>
 			<li>section 2</li>
		</ul>  
	<li>exercize n. 3 </li>
	<li>exercize n. 4 </li>
	<li>exercize n. 5 </li>
	<li>exercize n. 6 </li>
	<li>exercize n. 7</li>
</ul> 

were is present in the name's file:
<ul>
 <li>"img"  - the script automatize the generation of image file</li>
 <li>"modify" - the script have little change repsect original</li>
</ul>

The result are aviable in this repository:
[Report - MechanicalDesignMachineElements](https://github.com/frank1789/Report-MechanicalDesignMachineElements)
## Homework 1

1. Elaborate a Finite Element model of the Pratt truss bridge shown in the figure in order to determine nodal deflection, reaction forces and axial stresses.

The two bottom chords are subjected to a vertical distributed load with intensity of 20000 N/m. The dimensions are given in mm. One side of the bridge is pinned-supported, the other is roller-supported. The trusses have the following cross-sectional areas:

|Data:				 |		 |         |	 |
|--------------------------------|---------------|---------|-----|
|Bottom chord, top chord, struts:| A1 = 1000 mm2 |Material:|steel|
|Sway bracing:                   | A2 = 600 mm2  |E =	  |210GPa|
|Top lateral bracing:            | A3 = 400 mm2  |ν =      |0.3|

2. The shape of the bridge is then modified by moving the y coordinate of the nodes of the top chord by Δy1 and Δy2 as shown in the figure. Determine the values of Δy1 and Δy2 that minimize the maximum deflection

Please provide list of commands!

## Homework2
Using beam elements, build up a FE model of the hook shown in the Figure. Determine the maximum displacement, the maximum bending stress, shear and bending moment diagrams. Compare the results obtained considering the cross-sections 1 and 2 shown below. Discuss the need of mesh refinement.

|Data: |         |      |
|------|---------|------|
|F=20kN| E=205GPa| υ=0.3|

## Homework 3

|DATA:|    |
|-----|----|
|D/d =| 1.4|
|r/d =| 1/20|
|R =  |(D−d)/2|
|Material:| steel|
The figure illustrates a shouldered shaft carrying a relief groove to reduce the notch stress concentration effect. The shaft is subject to an axial load F. Using axisymmetric plane elements, build up a FE model that allows:

1. determining the stress concentration factor in the absence of the relief groove. Carry out a convergence analysis and compare the obtained result with solutions available in the literature.
2. determining the stress concentration factor as a function of the non-dimensional position x of the relief groove. Try to identify an optimal position. Use a mesh refinement level similar to that obtained in the convergence analysis carried out in point 1).

The stress concentration factor is defined as: Kt = σ1,max; σ1,max: maximum first
principal stress in the model; $Snet = F/((π/4) \times d^2)$
It is required to create a mapped mesh at least in the neighbourhood of the fillets of the shoulder and at the groove. Pay attetion to avoid distorted elements. Apply the axial force as a uniformly distributed pressure.
  
##  Homework 4
The figure illustrates a T pipe connector to be used in a hydraulic circuit subject to internal pressure pi. Using shell elements and taking into account the symmetry, build up a FE model composed of a mapped mesh that allows:

1. determining (meridional and circumferential) membrane stresses far from the junc- tion between the two pipes;
2. determining membrane and bending stress distribution along the periphery of the pipes’ junction.


## Homework 5
 The T pipe connector analyzed in HW 4 is now filletted at the junction between the two pipes to reduce the stress concentration factor. Using brick elements, build a sub- model able to estimate the stress distribution along the periphery of the pipes’ junction on the base of the displacement field computed with the shell model developed in HW 4. It is required to:

1. check for the sensitivity of the results upon the location of the cutting boundaries of the submodel.

## Homework 6

|DATA:  |	|
|-------|-------|
|l = |50 mm		|
|g = |	2 mm	|
|t = |	1.5 mm	|
|wp = |	25	|
|Rp = |	4	|
|Rd = | 3		|
|= | 4t|
|F = |100 kN		|
|**Blank:**|	S355JR steel	|
|E =| 	205 GPa	|
|σy =| 	355 MPa	|
|Ep =|	 4GPa	|

The figure schematically illustrates the deep drawing of a metal sheet (blank). During the forming process, the blank is pressed against the die applying a preload F, then the punch is gradually displaced by δ in order to push the blank inside the die cavity. The stiffness of punch, die and blank holder is assumed to be much higher than that of the blank. The friction cofficient is 0.1. Using axisymmetric plane elements, build a FE model able to simulate the forming process. In particular it is required to:

1. determine the distribution of the Von Mises equivalent stress at the end of the travel of the punch and the maximum axial force applied to the punch.
2. determine the punch stroke that maintains the maximum absolute hoop strain below 5%.
3. determine the residual stress distribution on the top and the bottom surface of the blank after the punch removal.
4. determine the elastic springback, i.e. the difference in axial displacement prior to and after the punch removal of the points lying on the blank midplane.

## Homework 7
|DATA:|    |
|-----|----|
|D/d =| 1.4|
|r/d =| 1/20|
|R =  |(D−d)/2|
|Material:| steel|
Determine the stress concentration factor (defined as ratio between the maximum first principal stress in the model and the remote stress acting on the cross-section with diameter d), in the presence and in the absence of the optimized relief groove analyzed in Homework 3, when the shaft is subject to uniform bending and torsional moment.
Please provide list of commands!
