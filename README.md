# Halo Orbit Solvers

All work here has been moved to [Halo-Explorations](https://github.com/cadojo/Halo-Explorations)!

## Summary
This repository contains a [report](/Report/Carpinelli_Halo_Solvers.pdf) and a 
[Pluto notebook](/Code/Halo%20Orbit%20Solvers.pdf) which which implement
analytical and numerical Halo Orbit solvers with the 
[Julia Programming Language](https://julialang.org). The primary source for this 
project is [Rund's Masters Thesis](https://digitalcommons.calpoly.edu/theses/1853/)
at Cal Poly. In addition to implementing Halo Orbit solvers, the report and notebook
also summarize how invariant manifolds about Halo Orbits can be used to design
low-cost interplanetary transfers. This project was completed as part of the
University of Maryland's graduate astrodynamics course, ENAE601.

## Background
Halo orbits are theoretically perfectly periodic orbits about equilibrium positions (a.k.a. 
[Lagrange points](https://en.wikipedia.org/wiki/Lagrange_point))
within the Circular Restricted Three-body Problem. All Halo Orbits are surrounded by 
stable and unstable manifolds. These manifolds can be used to carry a spacecraft closer
to a desired destination without spending fuel. As [Rund](https://digitalcommons.calpoly.edu/theses/1853/)
shows, this can be used to drastically lower the fuel costs required for interplanetary trajectories.
