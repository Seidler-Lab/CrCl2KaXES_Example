# CrCl2 Kalpha XES Example

FPLO: https://www.fplo.de/get-a-license/
Quanty: https://quanty.org/download

These scripts are built for a linux environment and require Quanty and FPLO binaries to be added to path. Please see the slides and files from the 13:30 - 15:00 Wednesday session of the 2019 Heidelberg workshop programme for more information about the DFT + MLFT codes: https://quanty.org/workshop/heidelberg/october_2019/programme

First, update the 0_RunCrCl2FPLO.Quanty and 1_RunCrCl2_WF.Quanty scripts to use whatever FPLO version sepecific binaries you have.
Then, using an up to date quanty binary, run
```
quanty 0_RunCrCl2FPLO.Quanty; quanty 1_RunCrCl2_WF.Quanty; quanty 2_XES.Quanty
```

Please Cite
- C. A. Cardot, J. J. Kas, J. E. Abramson, J. J. Rehr, and G. T. Seidler, *Core-to-core X-ray emission spectra from Wannier based multiplet ligand field theory*, https://doi.org/10.1016/j.elspec.2024.147419
- M. W. Haverkort, M. Zwierzycki, and O. K. Andersen, *Multiplet ligand-field theory using Wannier orbitals*, https://journals.aps.org/prb/abstract/10.1103/PhysRevB.85.165113

