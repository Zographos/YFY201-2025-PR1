# YFY201-2025-PR1

# Shannon Entropy & Information Content in RHF Atomic Densities (Z = 2–10)

## Introduction

Information-theoretic measures provide a quantitative window into the complexity and uncertainty of quantum systems. In particular, the **Shannon entropy** captures how delocalized an electron’s wavefunction is, beyond what simple moments or variances can convey.  Complementary metrics and divergence measures (**Kullback–Leibler, Jensen–Shannon**), probe additional aspects of an atomic electron density and its deviation from idealized reference models.

In this project we apply these tools to the **second-period atoms** (He through Ne).  We start from Hartree–Fock (RHF) radial wavefunctions expanded in Slater-type orbitals, and compute a suite of information-theoretic quantities from the resulting electron densities.

- Shannon entropies $S_r$ and $S_k$  
- The variance-dependent entropy bound $S_{\max}$  
- Onicescu’s information measure $O$  
- Fisher information $I$  
- The order parameter $\Omega$  
- Symmetrized Kullback–Leibler and Jensen–Shannon divergences against two reference models:  
  1. A hydrogenic 1s density fixed by the first ionization potential  
  2. A Thomas–Fermi statistical density  

All code and data used to reproduce these results live in this repository.

## Requirements

- Python 3.8+  
- numpy, pandas, scipy, matplotlib, joblib  
- Jupyter Notebook  
