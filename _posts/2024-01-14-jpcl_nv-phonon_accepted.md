---
title: "Quantum vibronic effects on the excitation energies of the nitrogen-vacancy center in diamond"
date: 2024-01-14T20:30:00-06:00
---
When a pair of adjacent carbon atoms within a diamond crystal is replaced with a nitrogen atom and a lattice vacancy,
a photoluminescent point defect, known as the nitrogen-vacancy (NV) center in a diamond, is created. 
Negatively charged NV-center in diamond acts as a pseudo-2-level spin system and the spin information can be read 
using the optically-detected magnetic resonance (ODMR) technique. 
Therefore, the NV-center has the potential to be used as a solid-state spin qubit with the promise to revolutionize 
emerging quantum technologies working near room temperature. 
The key to unlocking its true potential lies in understanding the electronically excited states,
an arena explored through rigorous quantum mechanical calculations. 
While an array of first-principles quantum calculations,
each employing distinct approaches to tackle the electron correlation problem, 
had been explored, the resulting vertical excitation energies (VEE) consistently 
exhibited discrepancies of several hundred meV compared to experimental values. 

![Image](/assets/images/pubs/jpcl2024_1.png)

To unravel this mystery, we decided to explore the impact of the quantum vibronic effect on VEEs, 
which has been overlooked in previous studies. 
To sample the quantum internuclear vibrations, we used stochastic methods, 
as implemented in the open-source [PyEPFD](https://pyepfd.readthedocs.io) software package 
that I have been developing since 2020. 
To describe the excited states, we used the extremely efficient time-dependent density functional theory implementation 
of the open-source [WEST](https://west-code.org/) software package. 
We found that quantum vibronic effects introduce dynamic Jahn-Teller splitting of the doubly degenerate excited states, 
even at absolute zero, leading to a VEE renormalization with a magnitude exceeding 180 meV. 
The inclusion of these renormalizations not only reconciled theory with experiment 
but also underscored the paramount importance of considering quantum vibronic effects in such calculations.

Throughout our exploration, we critically evaluated several standard approximations 
commonly employed in first-principles calculations of quantum vibronic effects. 
This scrutiny not only deepened our understanding of the intricacies involved but also 
served as a valuable checkpoint for the broader scientific community. 
Our journey into the quantum world not only sheds light on the dynamics of NV-center excitations 
but also challenges prevailing assumptions in theoretical frameworks. 
For a detailed dive into our findings, you can explore the following preprint: 
[arXiv:2401.06745 ](https://arxiv.org/abs/2401.06745)
which is accepted in 
[J. Phys. Chem. Lett. (currently in Press)](https://doi.org/10.1021/acs.jpclett.3c03269). 
