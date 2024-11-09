## Sound Wave Propagation Simulator
This simulator models sound wave propagation under various environmental conditions, using the Finite Difference Time Domain (FDTD) method. Configurable and precise, the simulator is a powerful tool for analyzing sound behavior based on key variables such as temperature, distance, and type of gaseous medium.

## Technical Overview
### FDTD Implementation for Wave Simulation
The simulation employs the FDTD method to compute the evolution of sound waves in time and space. To ensure stability and accuracy, it adheres to the Courant-Friedrichs-Lewy (CFL) condition:

$$
\frac{c \cdot \Delta t}{\Delta x} \leq 1
$$

where:
- \( c \) is the wave propagation speed,
- \( $\Delta$ t \) is the time step size, and
- \( $\Delta$ x \) is the spatial step size.

## Simulator Features
1. Customizable Propagation Conditions: Configurable variables such as temperature, gas type, microphone distances, and wave type (Gaussian pulse or impulse) enable the study of different sound propagation scenarios.

2. Simulation of Reflections and Perturbations: Implements reflective boundary conditions that mimic walls at the tube ends, generating interference and oscillations in wave behavior.

3. Comparison Across Gases: Simulates wave behavior in different gases (air, helium, carbon dioxide), each with unique density and heat capacity properties, demonstrating how the medium affects propagation speed.

-- 

python -m venv venv
python -m pip install jupyter
