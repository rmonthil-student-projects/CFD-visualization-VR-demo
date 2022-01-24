# CFD Visualization VR Demo
Demo of the VR visualization of a result of computational fluid dynamics.

# Requirements
You will need a Head-Mounted Display device and optionally a game controller.

# Using
Just download or clone the project :
```user
git clone https://github.com/LeDernier/CFD_Visualization_VR_demo.git
```
Wire all your HDM and optionally the controler and run :

```user
cd CFD_Visualization_VR_demo
./demo.x86_64
```

# Simulation
The simulation is the case of an injector. A fluid is injected in an external domain through a tiny hole (~ 150 micrometers). 
You will see :
* in green : contours of vorticity
* in red : contours of vapor rate
* in blue : velocity field, the bigger the arrow is, the greater is the velocity.
* in white : the geometry

Results come from **F. Giussani, F. Piscaglia, J. Hélie, N. Lamarque, Int. Journal of Multiphase Flow, submitted, 2019** 
and the simulations have been performed on **CINES** and **ANL** supercomputer platforms.
