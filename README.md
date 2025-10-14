# <ins> Computational Physics projects: </ins>

This repository serves as a showcase of my coding projects that I have undergone as part of my undergraduate Physics degree, alongside demonstrating new projects that serve to push my creativity and coding knowledge.

## <ins> Project 1- Numerical integration of differential equations:  </ins>
The main aim of this project was to investigate the effectiveness of models of spring-mass systems for various damping coefficients and forces over a small time period.
- Objective- solve the equation of motion for a damped harmonic oscillator:

$$
mx^{''}(t)+bx^{'}(t)+kx(t)=F(t)
$$

- Methods implemented:
  - Euler method. 
  -  Improved Euler method.
  -  Verlet method.
  -  Euler-Cromer method.
 
- Key features:
  - Visualisation of the motion of a spring-mass system.
  - Allowing for adjustable initial parameters.
  - Investigation of resonance and sudden applied force scenarios.

- Technical skills:
   - Understanding the Physics behind multiple varied methods, as well as the limitations to justify deviations from a solution.
   - Accurate error propagation to signify precise fits.
   - Libraries predominantly used: numpy and matplotlib.

## <ins> Project 2- Monte Carlo simulation:  </ins>
Investigating the core principles of randomness and how to correctly model neutron behaviour in various materials was the intended goal of this project to allow for analysis of the application of material properties in areas such as nuclear physics.
- Objective- Succesfully run an accurate, large-scale Monte Carlo simulation in water, graphite and lead.
- Methods implemented:
  - Pseudo-random numbers.
  - Monte Carlo method.

- Key features:
  - Investigation and visualisation of how computers can model randomness.
  - 3D models of the various scattering processes from fired neutrons on materials.
  - Accurately observing the ideal thickness for attenuation.

- Technical skills:
  - Optimisation of code to run in <45s.
  - Coding 3D environments to visually inspect the simulation.
  - Applying data from the simulations to understand ideal material characteristics.
  - Libraries predominantly used: numpy, matplotlib and numba.

## <ins> Project 3- Geolocation (in progress): </ins>
An ongoing project that seeks to allow for the understanding and visualisation behind how GPS and geolcation are used and optimised to allow for modern day life.
- Project aims:
    - Basic geometric calculation and visualisation of how GPS towers allow for an object's location in 2D.
    - Expanding the calculation to a 3D environment and how varied terrain can affect the accuracy.
    - Further advancing from a local 3D environment to a spherical model of the Earth; considering satellite motion.
    - Investigation of time accuracy and the quantum effects e.g. time dilation.
