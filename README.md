# corecollapse


Data release supporting [arXiv:1602.06952](https://arxiv.org/abs/arXiv:1602.06952). 

#### Numerical simulations of stellar collapse in scalar-tensor theories of gravity
We present numerical-relativity simulations of spherically symmetric core collapse and compact-object formation in scalar-tensor theories of gravity. The additional scalar degree of freedom introduces a propagating monopole gravitational-wave mode. Detection of monopole scalar waves with current and future gravitational-wave experiments may constitute smoking gun evidence for strong-field modifications of General Relativity. We collapse both polytropic and more realistic pre-supernova profiles using a high-resolution shock-capturing scheme and an approximate prescription for the nuclear equation of state. The most promising sources of scalar radiation are protoneutron stars collapsing to black holes. In case of a Galactic core collapse event forming a black hole, Advanced LIGO may be able to place independent constraints on the parameters of the theory at a level comparable to current Solar-System and binary-pulsar measurements. In the region of the parameter space admitting spontaneously scalarised stars, transition to configurations with prominent scalar hair before black-hole formation further enhances the emitted signal. Although a more realistic treatment of the microphysics is necessary to fully investigate the occurrence of spontaneous scalarisation of neutron star remnants, we speculate that formation of such objects could constrain the parameters of the theory beyond the current bounds obtained with Solar-System and binary-pulsar experiments.


### Waveforms in scalar-tensor theories


We provide data files of the gravitational-wave waveforms presented in our paper. In particular, time-domain and frequency-domain waveforms of all runs entering Figs. 5.3,5.4 and 5.5 are provided.

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

Definitions and conventions for `h(t)` and `sqrt(S(f))` are given in the paper. All numerical setups are specified in Sec.4 of our paper: in particular, signals are extracted at r_ext = 3e9cm and computed for an optimally oriented source placed at D=10kpc from the detector. The time-domain waveforms provided are raw data and include the initial unphysical transient due to the initialization of the scalar field. Frequency-domain waveforms have been computed selecting a time window t-r_ext=[0.006,0.6] as specified in Sec.4.


### Animations

We also provide aninmated versions of Fig. 5.1 (files `evolution*`). Here is a [YouTube playlist](https://www.youtube.com/playlist?list=PLVjP4QK1oHulxnqt4lgREQo9tNeeit-TX) as well.



