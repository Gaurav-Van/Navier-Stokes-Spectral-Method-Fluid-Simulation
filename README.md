# Navier-Stokes-Spectral-Method-Fluid-Simulation
This Repository Contains code related to Simulation Fluid Following Navier-Stokes Spectral Method under the assumption of it being incompressible viscous fluid

## Assumption 
Navier-Stokes equations `(incompressible viscous fluid)` with a Spectral method

![image](https://github.com/user-attachments/assets/f44b659a-eca4-4eed-b218-cd5f7b431469)

## Spectral Method 
A spectral method represents the numerical solution to a partial differential equation as a sum of global basis functions with coefficients as the unknowns to be solved for. Here we will consider the Fourier basis, which is ideal for representing continuous solutions on a periodic domain. Such a method can then use the Fast Fourier Transform (FFT) algorithm to transform the solution on the physical domain x into Fourier space, where the solution becomes a sum of waves each described by a wavenumber k. 

<hr>

## Resources and Reference 

#### Best Video for Description and Derivation of Navier-Stokes Equation 
[![Description and Derivation of Navier-Stokes Equation](https://img.youtube.com/vi/NjoMoH51UZc/0.jpg)](https://www.youtube.com/watch?v=NjoMoH51UZc)

#### Best Video for an Overview of Nature of Navier-Stokes Equation 
[![Overview of Nature of Navier-Stokes Equation](https://img.youtube.com/vi/XoefjJdFq6k/0.jpg)](https://www.youtube.com/watch?v=XoefjJdFq6k)

#### Medium Article from where i got the inspiration to study about Navier-Stokes Equation
[Create Your Own Navier-Stokes Spectral Method Fluid Simulation (With Python)](https://medium.com/gitconnected/create-your-own-navier-stokes-spectral-method-fluid-simulation-with-python-3f37405524f4)<br><br>
`Author` is Philip Mocz. Special Thanks to him 

<hr>

## Fun Fact 
The Navier-Stokes Equation is one of the `Millenium Prize Problems` 

![image](https://github.com/user-attachments/assets/c5b67ff8-06bc-4095-b7b0-e4626de11acf)

<hr>

## Recent Advancements
There have been some interesting developments in 2024 regarding the existence and smoothness of solutions to the Navier-Stokes equation. A notable paper by Brian David Vasquez Campos presents a smooth solution to the Navier-Stokes equation. This solution is constructed by studying the iteration of a product defined over a space of functions dominated by Fourier caloric functions that decrease rapidly. Additionally, the paper shows the existence of a curve of entire vector fields of order 2 that extends the solution to the complex domain for positive time (https://arxiv.org/pdf/2405.07929)

This is a significant step forward in understanding the Navier-Stokes equation, which is fundamental in fluid dynamics and has implications for various fields, including weather forecasting, aircraft design, and biomedical engineering.









