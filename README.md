# Subensemble acceptance method

## Description

This repository contains material related to a subensemble acceptance method (SAM).
The SAM is a procedure to evaluate the effect of exact global conservation laws on cumulants of a random number distribution in a subsystem.

## SAM-1.0

The SAM was originally developed to describe cumulants of a conserved quantity measured in a subvolume of a uniform thermal system.
The results were first obtained for a case of single conserved charge in
- V. Vovchenko, O. Savchuk, R. Poberezhnyuk, M.I. Gorenstein, V. Koch, *Connecting fluctuation measurements in heavy-ion collisions with the grand-canonical susceptibilities*, [Phys. Lett. B 811, 135868 (2020)](https://doi.org/10.1016/j.physletb.2020.135868) [[arXiv:2003.13905 [hep-ph]](https://arxiv.org/abs/2003.13905)]

The SAM was extended for the case of multiple conserved charges in
- V. Vovchenko, R. Poberezhnyuk, V. Koch, *Cumulants of multiple conserved charges and global conservation laws*, [JHEP 10, 089 (2020)](https://doi.org/10.1007/JHEP10(2020)089) [[arXiv:2007.03850 [hep-ph]](https://arxiv.org/abs/2007.03850)]
  
### Material

- A Wolfram Mathematica notebook [**SAM-MultipleConservedCharges.nb**](SAM-MultipleConservedCharges.nb) allows one to express an arbitrary cumulant of conserved charges up to sixth order in terms of the grand-canonical susceptibilities and acceptance parameter &alpha;. The final expressions are written using the notation commonly employed in QCD literature.

## SAM-2.0

SAM-2.0 extends the original method to non-uniform systems and arbitrary subsystems (acceptances), such as that in momentum space. This method is documented in
- V. Vovchenko, *Correcting event-by-event fluctuations in heavy-ion collisions for exact global conservation laws with the generalized subensemble acceptance method*, [arXiv:2106.XXXXX [hep-ph]](https://arxiv.org/abs/2106.XXXXX)

### Material

- A Wolfram Mathematica notebook [**SAM2.0-conserved**](SAM2.0-conserved.nb) allows one to express cumulants of a conserved quantity measured in the acceptance and constrained by exact global conservation in terms of the unconstrained (''grand-canonical'') cumulants inside and outside the acceptance. Calculations proceed recursively up to arbitrary order.
- A Wolfram Mathematica notebook [**SAM2.0-conserved-and-nonconserved**](SAM2.0-conserved-and-nonconserved.nb) allows one to express the joint cumulants of conserved and non-conserved quantities in the acceptance and constrained by exact global conservation in terms of the unconstrained (''grand-canonical'') joint cumulants inside and outside the acceptance. Calculations proceed recursively up to arbitrary order.

## Attribution

Publications using either the SAM or SAM-2.0 should include references to the corresponding papers listed above.

*Copyright (C) 2020-2021 Volodymyr Vovchenko*
