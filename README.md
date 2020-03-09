# Kidney-ColIV-Remodel
# Table of contents
- [About](#About)
- [Authors](#Authors)
- [Abstract](#Abstract)  
- [Installation](#Installation)
- [Citing](#Cite)
- [License](#License)
- [Acknowledgements](#Acknowledgements)

Tags:
  - Kidney
  - Capillary
  - Biomechanics
  - Growth
  - Remodeling
  - Stability
  
# About
- This repository contains the code used for generating data in the paper "Glomerular Filtration and Podocyte Tensional Homeostasis: Importance of the Minor Type IV Collagen Network" by Bersie-Larson et al. 

# Authors
- Lauren M. Bersie-Larson (1)
- Lazarina Gyoneva (1)
- Daniel J. Goodman (1)
- Kevin D. Dorfman (2)
- Yoav Segal (3, 4)
- Victor H. Barocas* (1)

## Affiliations:
 - (1) Department of Biomedical Engineering, University of Minnesota Twin-Cities
 - (2) Department of Chemical Engineering and Materials Science, University of Minnesota Twin-Cities
 - (3) Division of Renal Diseases and Hypertention, Department of Medicine, University of Minnesota Twin-Cities
 - (4) Minneapolis VA Healthcare System
 
## * Corresponding Author Information
7-105 Nils Hasselmo Hall
312 Church St SE
Minneapolis, MN 55455 \
baroc001@umn.edu

#  Abstract
The minor type IV collagen chain, which is a significant component of the glomerular basement
membrane in healthy individuals, is known to assemble into large structures (supercoils) that
may contribute to the mechanical stability of the collagen network and the glomerular
basement membrane as a whole. The absence of the minor chain, as in Alport syndrome, leads
to glomerular capillary demise and eventually to kidney failure. An important consideration in
this problem is that the glomerular capillary wall must be strong enough to withstand the
filtration pressure and porous enough to permit filtration at reasonable pressures. In this work,
we propose a coupled feedback loop driven by filtration demand and tensional homeostasis of
the podocytes forming the outer portion the glomerular capillary wall. Briefly, the deposition of
new collagen increases the stiffness of basement membrane, helping to stress shield the
podocytes, but the new collagen also decreases the permeability of the basement membrane,
requiring an increase in capillary transmural pressure drop to maintain filtration, and the
resulting increased pressure outweighs the increased glomerular basement membrane stiffness
and puts a net greater stress demand on the podocytes. This idea is explored by developing a
multiscale simulation of the capillary wall, in which a macroscopic (µm-scale) continuum model
is connected to a set of microscopic (nm-scale) fiber network models representing the collagen
network and the podocyte cytoskeleton. The model considers two cases: healthy remodeling, in
which the presence of the minor chain allows the collagen volume fraction to be increased by
thickening fibers, and Alport syndrome remodeling, in which the absence of the minor chain
allows collagen volume fraction to be increased only by adding new fibers to the network. The
permeability of the network is calculated based on previous models of flow through a fiber
network, and it is updated for different fiber radii and volume fractions. The analysis shows that
the minor chain allows a homeostatic balance to be achieved in terms of both filtration and cell
tension. Absent the minor chain, there is a fundamental change in the relation between the
two effects, and the system becomes unstable. This result suggests that mechanobiological or
mechanoregulatory therapies may be possible for Alport syndrome and other minor-chain
collagen diseases of the kidney.

# Installation

# Citing

# License

# Acknowledgements
This work was supported by the National Science Foundation (CMMI-1300649), the National
Institutes of Health (R01-EB005813) and with resources and the use of facilities at the
Minneapolis VA Health Care System. LMB was supported in part by NIH U54CA210190
(University of Minnesota Physical Sciences in Oncology Center to P. P. Provenzano). Simulations
were made possible by a resources grant from the Minnesota Supercomputing Institute.
