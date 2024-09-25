---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Hi! I'm Harshal, and I am currently pursuing my Master of Science (Research) in Space Science Engineering degree at the Department of Astronomy, Astrophysics, and Space Engineering at IIT Indore. The Milky Way is found to contain two stellar disks, the thin disk extending to a height of a few hundred parsecs and the thick disk extending to a height of a few kiloparsecs. Learning about the structure of the galaxy helps us understand the evolution and the processes that resulted in the creation of the galaxy as it exists now. My current work involves finding the thin and thick stellar disk in nearby external local spiral galaxies.

My current Work 
======
The vertical structure of the disk can be calculated by solving the coupled Poisson's-Boltzmann equation. The gravity in this equation can be interpreted through the mass present, inferred through observations (optical and radio), and the pressure is estimated through observed velocity dispersion. However, due to a lack of spectroscopic information over entire optical disks, earlier studies calculated the stellar velocity dispersion through an analytical formula.

So, we use the IFU data of the galaxy NGC 551 from Data Release 3 (DR3) of the CALIFA integral field unit (IFU) survey and estimate the vertical velocity dispersion in its stellar disk. Assuming the stellar disk to be in vertical hydrostatic equilibrium under the force field of the gas disks and the dark matter halo, we self-consistently solve the joint Poisson's equations of hydrostatic equilibrium to obtain a three-dimensional density distribution of the stellar disk. Using this density distribution and the rotation curve (estimated using HI data), we built a dynamical model of the stellar disk in NGC 551. This dynamical model is then projected into the sky-plane with the observed inclination and convolved with the telescope point spread function to produce a model surface density map, which is equivalent to the observation. We then compare this map with the observed surface density map to investigate the existence of a multi-component stellar disk in NGC 551.

Software Skill Learned
======
During the 2 years of my master's degree, I have acquired the following skills:

1) Photometry
   I have learned to derive the surface density profile from the telescope data for optical and infrared using [photutils](https://photutils.readthedocs.io/) and [MGEFit](https://www-astro.physics.ox.ac.uk/~mxc/software/#mge) python softwares.
   
2) Galactic Spectroscopy
   I have learned and understood the algorithm behind the [PyPIPE3D](https://pypi.org/project/pypipe3d/) pipeline code and obtained the stellar velocity dispersion from the spectrum obtained from CALIFA integral field unit.
   
3) Markov Chain Monte Carlo
   I have learned to apply Markov Chain Monte Carlo (MCMC) using [emcee](https://emcee.readthedocs.io/) python package for fitting the total observed rotational velocity by decomposing it into stellar, gas, and dark matter halo components and later using the velocity components for mass modeling the galaxy.
   
4) Galactic Modeling
   I have learned to build a 3D model by solving the coupled Poisson's-Boltzmann equation in parellel computation using [MPI](https://mpi4py.readthedocs.io/) python package.
