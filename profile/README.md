### This organization contains the current developers of the Phoebe project. 

Phoebe is maintained by [Jenny Coulter](https://www.simonsfoundation.org/people/jennifer-coulter/), currently at the Flatiron Institute (CCQ), in collaboration with the [Kozinsky group](https://mir.g.harvard.edu/) at Harvard University and the [Simoncelli group](https://www.apam.columbia.edu/michele-simoncelli) at the University of Cambridge (soon moving to Columbia University).

If you are interested in contributing to the development, please reach out to us by opening a discussion on the Phoebe repository or writing by email to discuss before beginning. 

-------------------------
### About Phoebe 
Phoebe is an open-source code for the ab-initio computation of electron and phonon transport properties of crystalline materials.

It is designed to take advantage of HPC systems via MPI-OpenMP hybrid parallelism, memory-distributed computing via ScaLAPACK, and GPU accelerated calculation of scattering rates.

Tutorials, documentation of functionality and underlying theory can be found at:
  * [Homepage](https://mir-group.github.io/phoebe/)
  * [Tutorials/Documentation](https://phoebe.readthedocs.io/en/develop/introduction.html)

For further questions and feature requests, please post on the discussions page for the git repo.
If you feel you've found a bug or seen some unexpected behavior, please let us know by opening a git issue. 

-------------------------
### Partially supported by:

<div class="inline-block">
<img src="https://github.com/phoebe-team/phoebe/blob/gh-pages/pictures/logos/logo-banner.png" height="70"/>
</div>

-------------------------
### Current functionalities
#### Electronic Transport

   * Electron-phonon and phonon-electron scattering rates by Wannier interpolation
   * Electron-phonon scattering within the electron-phonon averaged (EPA) approximation
   * Electronic transport coefficients (mobility, conductivity, thermal conductivity, and Seebeck coefficient)

#### Phonon Transport

   * Phonon (lattice) thermal conductivity, including: 
     * 3-phonon scattering from thirdOrder.py/ShengBTE or Phono3py force constants
     * Boundary, isotope, and phonon-electron scattering contributions
     * Lattice thermal conductivity calculations including both ph-ph and ph-el scattering 

#### And more...

   * BTE solutions by RTA, iterative, variational, and relaxon solvers
   * Calculation of electron and phonon linewidths or relaxation times on a path
   * Wigner transport equation correction for electrons and phonons 
   * Hydrodynamic transport properties (viscosity) for electrons and phonons
