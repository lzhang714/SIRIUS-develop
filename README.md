

SIRIUS is domain specific library for plane wave DFT calculations. The code is developed and mantained by CSCS Switzerland.

Please check the original repository: https://github.com/electronic-structure/SIRIUS



This repository is a snapshot of the develope branch of SIRIUS. It was forked on Feb 22, 2020. 

We intend to experiment a few things:

1. To improve the performance of GGA-PBE functional(s). This part is limited to FP-LAPW calculation.

2. To realize a Wannier function downfolding procedure exactly in the same way as in Exciting-Plus FP-LAPW code, then do maximum localization following that done in the EXCITING(Berlin) FP-LAPW code. This part is also limited to FP-LAPW calculation at the moment.

3. To test the mini app of calculating band structure (part of dft_loop). This is also required by Wannier downfolding (for comparing with reconstructed bands).


