# corecollapse

Data release supporting

- *Numerical simulations of stellar collapse in scalar-tensor theories of gravity.*
Davide Gerosa, Ulrich Sperhake, Christian D. Ott.
Class. Quantum Grav. 33, 13, 135002 (2016).
[arXiv:1602.06952](https://arxiv.org/abs/arXiv:1602.06952)


## Credits

You are welcome to use our software/data in your research. We kindly ask you to cite the paper above. If you want to cite this data release specifically, the DOI code is: [![DOI](https://zenodo.org/badge/145436741.svg)](https://zenodo.org/badge/latestdoi/145436741).

## Waveforms in scalar-tensor theories

We provide [data files](https://github.com/dgerosa/corecollapse/tree/master/waveforms) of the gravitational-wave waveforms presented in our paper. In particular, time-domain and frequency-domain waveforms of all runs entering Figs. 5.3, 5.4 and 5.5 are provided.

Files are named according to the following convention:

    model_gamma1_gamma2_gammath_alpha0_beta0_TD/FD.dat

where:
- `model=WH12,WH40` is the initial profile;
- `gamma1`, `gamma2` and `gammath` are the adiabatic indexes entering the EOS;
- `alpha0` and `beta0` are the scalar-tensor theory parameters;
- `TD` or `FD` stands for time-domain and frequency-domain waveforms, respectively.

Files have two columns:

- `time | h(t)` for time-domain waveforms;
- `frequency | sqrt(S(f))` for frequency-domain waveforms.

Definitions and conventions for `h(t)` and `sqrt(S(f))` are given in the paper. All numerical setups are specified in Sec.4 of our paper: in particular, signals are extracted at r_ext = 3e9cm and computed for an optimally oriented source placed at D=10kpc from the detector. The time-domain waveforms provided are raw data and include the initial unphysical transient due to the initialization of the scalar field. Frequency-domain waveforms have been computed by selecting a time window t-r_ext=[0.006,0.6] as specified in Sec.4.


### Animations

We also provide animated versions of Fig. 5.1 (files `evolution*`). Here is a [YouTube playlist](https://www.youtube.com/playlist?list=PLVjP4QK1oHulxnqt4lgREQo9tNeeit-TX)  with all animations. [Files](https://github.com/dgerosa/corecollapse/tree/master/animations) are available as well.

https://github.com/user-attachments/assets/71d20bd1-f5d1-49dd-927d-01eb6bab32ae

https://github.com/user-attachments/assets/94adb49a-0248-4cd7-96ef-8e66b796dcae

https://github.com/user-attachments/assets/56c7bfbf-f92b-4581-afee-e666c58bee09



