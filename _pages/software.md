---
permalink: /software/
title: "Software"
excerpt: "Packages I develop and other commercial and open-source packages I use."
toc: true
---
Here you will find the computational chemistry/physics/materials-science packages 
that I developed and also the commercial/open-source packages I routinely use for 
my research work.
  
## Packages I develop and maintain

I developed the following three open-source packages.

### 1. PyEPFD
![](https://github.com/arpank-2380/PyEPFD/raw/master/docs/source/pyepfd_logo.png){: style="margin-top: 0.5em;"}


PyEPFD [code repository](https://github.com/arpank-2380/PyEPFD) 
stands for a Python Library for Electron-Phonon coupling
from Finite Displacements.

PyEPFD provides a set of tools to compute electronic properties,
such as fundamental gap, at a finite temperature where
nuclear quantum effects are incorporated using harmonic approximation.
For that purpose, an additional ab-initio code is required that computes
the ab-initio forces and electronic properties such as eigenenergies of
the bands. PyEPFD also provides tools to analyze the validity of the
harmonic approximation if a Molecular Dynamics and/or Monte Carlo
trajectories are available. Currently, for the ab-initio part, PyEPFD
depends on [Qbox code](http://qboxcode.org/). However, it is very easy
to use pyEPFD with any ab-inito code of your choice. For more 
information see the [documentation](https://pyepfd.readthedocs.io/)

**Acknowledgement:** The development of PyEPFD is supported by the
Midwest Integrated Center for Computational Materials 
([MICCoM](https://miccom-center.org/)) 

### 2. LGCMC
![](https://github.com/arpank-2380/LGCMC/raw/master/LGCMC-logo.png)

LGCMC ([code repository](https://github.com/arpank-2380/LGCMC)) is a open-source FORTRAN package for Lattice Grand Canonical Monte Carlo Simulation for *ab initio* prediction of pure and mixed gas isotherms.

A grand canonical Monte Carlo simulates adsorption isotherms of pure 
and mixture of gases within a porous material. 
This approach imposes the condition of material equilibrium, i.e., the chemical 
potential of a species is equal in both gas and adsorbed phase. 
Usually simulation cells containing thousands of atoms are required and 
these are only feasible with force fields, which are often not adequate 
to describe the interatomic interactions. 
Sometimes, refitting force field parameters using *ab initio* calculations 
improves the interatomic descriptions but yet these refitted forcefileds are 
limited by the form of the adopted interatomic potential.
An alternative to force field fitting is to map the atomic degrees of
freedom of the adsorbate surface onto a coarse-grained description of 
adsorption sites. Such mapping can be made to utilize accurate *ab initio* 
energies using high-level quantum chemical methods 
such as coupled cluster theory. 
After coarse-graining, a GCMC simulation can be performed on
this coarse-grained model. **LGCMC** performs such kind of GCMC simulations on a
coarse-grained model to simulate pure and mixed gas adsorption isotherms. 
In this way it is possible to treat adsorbate-adsorbate lateral interactions 
explicitely, and thus, isotherm calculations can be performed avoiding 
any approximations, such as mean-field approximation.

**Acknowledgement:** Development of LGCMC (2013-2017) was supported by [International Max Planck Research School “Functional Interfaces in Physics and Chemistry”](https://www.fhi.mpg.de/imprs) and German Science Foundation ([DFG](https://gepris.dfg.de/gepris/projekt/172559843?language=en)) within the priority program 1570 “Porous media”.  

### 3. iPI-Qbox interface API
![](https://github.com/arpank-2380/ipi-qbox-interface/raw/master/ipi-qbox-logo.png)

This is an open source application program interface (API) designed to couple [Qbox](http://qboxcode.org/), a 
first principle molecular dynamics code with [i-PI](http://ipi-code.org/), 
a path-integral package, using  socket-based client server protocol. 
In an iPI---Qbox coupled simulation, 
[i-PI](http://ipi-code.org/) moves nuclei while 
[Qbox](http://qboxcode.org/) acts as the density-functional theory (DFT) 
engine that supplies forces and stress tensors from first-principles 
DFT calculation. 
iPI-Qbox interface API ([code-repository](https://github.com/arpank-2380/ipi-qbox-interface)) maintains constant communication 
between an i-PI server and several Qbox servers.
These simulations are extreamely useful to simulate nuclear quantum effects from first principles. 
    


## Commercial and open-source packages I use 

**Qbox:**

**Quantum Espresso:**

**VASP:**

**WEST:**

**Turbomole:**

**i-PI:**

