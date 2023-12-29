# Theory:

## Introduction to experiment
<div style="text-align: justify">

<center>

<img  src='./images/Flow_pattern.jpg' style="width:50%" >

<figcaption align = "center"><b>Fig.1 - Basic features of the flow past cylinder. (adapted from : Davenport, W.J. (2003))</b></figcaption>

</center>


Flow over a cylinder is a fundamental aerodynamics problem of practical importance. The flow field over the cylinder is symmetric at low values of the Reynolds number. As the Reynolds number increases, flow begins to separate behind the cylinder, causing vortex shedding, an unsteady phenomenon. In this experiment, a wind tunnel test  is conducted using conventional instrumentation, specifically a static pressure port. Many models present themselves to flow as cylinders of different cross sections. The flow pattern and the drag on a cylinder are functions of the Reynolds number <img  src='./images/teq1.png' style="width:8%">, based on the cylinder diameter $d$ and the undisturbed free-stream velocity U<sub>∞</sub>. The drag is usually expressed as a coefficient <img  src='./images/teq2.png' style="width:8%">, where D is the drag force per unit span. Cylinder exhibit varying flow patterns at different Reynolds numbers. The flow pattern at high Reynolds numbers (<img  src='./images/teq3.png' style="width:8%">) is sketched in Figures 1(a) and 1(b). When flow hits the cylinder, a stagnation point is formed at the leading edge, and the pressure at this point equals the stagnation pressure. The pressure coefficient there is, therefore, equal to 1 using the equation <img  src='./images/teq4.png' style="width:8%"> (see Figure 2 from Bertin and Smith, 1989). 

<center>
<img  src='./images/cylinder_graph.png' style="width:50%" >

<figcaption align = "center"><b>Fig.2 - Measured pressure ditributions on a circular cylinder with a theoretical distribution calculated assuming ideal flow. Angle theta defined in Figure 1 <br> (adapted from : Bertin and Smith(1989))</b></figcaption>
</center>


After the leading edge, the flow accelerates on both sides, producing a pressure drop (Figure 2). Immediately adjacent to the cylinder surface, a thin boundary layer is formed.



For Re<sub>D</sub> less than 400,000, the boundary layer remains laminar between the stagnation and flow separation points. The resulting flow pattern (Figure 1(a)) is termed sub-critical. The laminar boundary layer separates upstream of the maximum thickness (see Figure 1(a)). Separation occurs because the boundary layer anticipates the deceleration of the flow (and, therefore, a positive pressure gradient). The flow quickly becomes turbulent downstream of separation, and a broad wake is formed. The wake is unstable and rolls up into vortices shed anti-symmetrically at regular intervals from the cylinder (Figure 1(a)). The wake is called a von Kármán vortex street. Because of separation, the pressure remains low and approximately constant over the rearward face of the cylinder. A net imbalance of pressure forces on the cylinder (Figure 2) is caused, usually referred to as the pressure drag. Pressure drag accounts for about 90% of this regime's total drag on the cylinder. The remaining 10% is due to skin-friction drag - friction between the flow and the cylinder. Most skin-friction drag is produced on the forward face of the cylinder where the boundary layer is thin, and velocity gradients at the cylinder surface are large.

For Reynolds numbers greater than 400,000, the boundary layer becomes turbulent on the forward face of the cylinder. The resulting flow pattern (Figure 1(b)), termed super-critical, is associated with a much lower drag, and Cd is approximately 0.3. This drop in Cd is usually referred to as the drag crisis. The flow remains attached to the cylinder surface well past its maximum thickness. As a result, the wake is much narrower, the imbalance of pressure forces on the cylinder surface is much smaller, and the pressure drag is greatly reduced. This reduction swamps a small increase in skin-friction drag produced by the greater length of the boundary layer and its transition. The drag crisis need not always occur at ReD = 400,000, and roughness of the cylinder surface or unsteadiness in the free stream can cause boundary layer transition at a much lower Reynolds number.

Plots of pressure distribution and pressure coefficients along the surface of the cylinder demonstrate the flow separation.


</div>



## Mathematical Description:

I. By definition of Coefficient of pressure,
<center>
<img  src='./images/eq1.png' style="width:10%"> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; (1)
</center>


From Bernoulli's equation,

<center>
<img  src='./images/eq2.png' style="width:10%"> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; (2)
</center>

From eq. 1 and 2 

<center>
<img  src='./images/eq3.png' style="width:10%"> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; (3)
</center>

II. From potential flow theory,

<center>
<img  src='./images/eq4.png' style="width:10%"> &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; (4)
</center>


Where,

P    - Presure

C<sub>p</sub>  - Coefficient of presure

V    - Velocity

ρ - Density of fluid

θ  - Angle between oncoming flow directiona and port location.

Subscript

θ  - measurement port.

0       - Total, measured at settling chamber.   

∞  - Freestream, measured at inlet of test section. 

## Determining the pressure drag from surface-pressure measurements

The drag on a real cylinder is, of course, not zero and can be estimated from a measured pressure distribution as follows. Consider an element of the cylinder surface of length ds = rdθ as shown in Figure. The force per unit span on the element due to a pressure normal to the element is
<center>
<img  src='./images/eq5.png' style="width:15%">
</center>

The drag component of this force is the component acting in the direction of the free-stream velocity
<center>
<img  src='./images/eq6.png' style="width:10%">
</center>

The integral of this around the cylinder circumference gives the total drag on the cylinder per unit span d.
<center>
<img  src='./images/eq7.png' style="width:15%">
</center>

Now, it is conventional to work in terms of the non-dimensional drag coefficient and pressure coefficient, respectively:
<center>
<img  src='./images/eq8.png' style="width:11%">
</center>
<center>
<img  src='./images/eq9.png' style="width:10%"> 
</center>

where d is the cylinder diameter. We therefore have,

<center>
<img  src='./images/eq10.png' style="width:32%">
</center>


Or

<center>
<img  src='./images/eq11.png' style="width:32%">
</center>


the second integral is zero, giving,

<center>
<img  src='./images/eq12.png' style="width:15%">
</center>

This integration can be done numerically using Simpson's or the trapezium rule or by plotting C<sub>p</sub>cosθ vs. θ and measuring the area under the curve. θ is measured in radians.

The above estimate of C<sub>D</sub> takes account only of the pressure drag on the cylinder. In calculating this, however, it is fairly accurate, the main source of error probably being the numerical integration.
