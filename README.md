# Navier-Stokes-Spectral-Method-Fluid-Simulation
This Repository Contains code related to Simulation Fluid Following Navier-Stokes Spectral Method under the assumption of it being incompressible viscous fluid

## Assumption 
Navier-Stokes equations `(incompressible viscous fluid)` with a Spectral method

![image](https://github.com/user-attachments/assets/f44b659a-eca4-4eed-b218-cd5f7b431469)

## Spectral Method 
A spectral method represents the numerical solution to a partial differential equation as a sum of global basis functions with coefficients as the unknowns to be solved for. Here we will consider the Fourier basis, which is ideal for representing continuous solutions on a periodic domain. Such a method can then use the Fast Fourier Transform (FFT) algorithm to transform the solution on the physical domain x into Fourier space, where the solution becomes a sum of waves each described by a wavenumber k. 

<hr>

## Ressources and Reference 

#### Best Video for Description and Derivation of Navier-Stokes Equation 
[![Description and Derivation of Navier-Stokes Equation](https://img.youtube.com/vi/NjoMoH51UZc/0.jpg)](https://www.youtube.com/watch?v=NjoMoH51UZc)

#### Best Video for an Overview of Nature of Navier-Stokes Equation 
[![Overview of Nature of Navier-Stokes Equation](https://img.youtube.com/vi/XoefjJdFq6k/0.jpg)](https://www.youtube.com/watch?v=XoefjJdFq6k)

#### Medium Article from where i got the inspiration to study about Navier-Stokes Equation
[Create Your Own Navier-Stokes Spectral Method Fluid Simulation (With Python)](https://medium.com/gitconnected/create-your-own-navier-stokes-spectral-method-fluid-simulation-with-python-3f37405524f4)





