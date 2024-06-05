Brain teaser for thermodynamics types: 

What happens if you fill a sealed vessel with mostly water, but a little steam, and then heat it up almost to the 
critical temperature? Does the vessel end up filled with water, or steam?

We can get some intuition for this by plotting the specific volume of water as a function of temperature and pressure.
![water_volume_plot](https://github.com/dogiv/waterplot/assets/19434514/a85afe0d-9e0f-41d8-b13e-dafc90f8a3fa)

The left side of the plot here shows what happens at room temperature--water boils suddenly as the temperature rises to 100 C, 
making a sharp cliff where the volume increases from very small (liquid water) to very large (low-pressure steam). That huge 
change in specific volume also takes a lot of energy.

As the pressure increases, the boiling point rises--sharply at first, then more gradually. But the change in volume across
the phase boundary decreases, as the liquid water at the boiling point gets hotter and less dense, and the steam at the 
boiling point becomes highly compressed.

Eventually, the cliff edge peters out entirely and the transition becomes a smooth curve. This is the critical point 
(red dot in the image). But nothing happens suddenly at the critical point; just below it the transition from water to 
steam is barely noticeable.

This plot can also tell us a bit about supercritical water: if the temperature is above the critical temperature of 373 C 
by any significant amount, the density of the supercritical water is a lot like steam, even at very high pressure. Right 
around the critical temperature, extremely high pressures can force the density down into a range more like liquid water.

This view can also help answer a thermodynamic brain teaser: the vessel starts at some point on the cliff face, and since 
we are holding its volume constant, when we add energy it moves along the cliff face to the right (increasing temp and 
pressure), but it stays at the same height. Eventually it will get to the end of the cliff. Whether it hits the boundary 
at the bottom of the cliff (and becomes all liquid) or the top of the cliff (and becomes all steam) depends on whether the 
initial mix was, on average, above or below the critical density.

Run the script to generate a rotating 3d version of this diagram.
