### -> submitter ORCID (or name)

0000-0002-8628-3704

### -> slug

yang-2023-eqcycles

### -> license

CC-BY-4.0

### -> alternative license URL

_No response_

### -> model category

model published in study, community benchmark, forward model

### -> model status

completed

### -> associated publication DOI

https://doi. org/10.1029/2023GC010872

### -> model creators

Haibin Yang, 0000-0002-8628-3704
Louis Moresi, 0000-0003-3685-174X
Huihui Weng, 0000-0002-2936-2342
Julian Giordani, 0000-0003-4515-9296

### -> title

Numerical Modeling of Earthquake Cycles Based On Navier-Stokes Equations With Viscoelastic-Plasticity Rheology

### -> description

The numerical modeling method for long-term tectonic deformations
averages out the co-seismic fault displacement into thousands to tens of thousands of years, and neglects
near-fault damages of earthquakes; therefore, it may not be able to decipher fault activities in detail. Software
simulating earthquake rupture dynamics may not have a good estimation of background stress due to longterm
tectonic deformations. In this study, we develop a numerical framework that embeds earthquake rupture
dynamics into a long-term tectonic deformation model by adding inertial terms and using highly adaptive
time-stepping that can capture deformation at plate-motion rates as well as individual earthquakes. The inertia
term, which is neglected in long-term large-scale modeling methods, is considered to simulate the dynamic
rupture processes. The rate-and-state frictional relationship for co-seismic fault slip is implemented in
viscoelastic-plastic earth. Benchmarks of viscous flow, viscoelastic wave propagation and earthquake cycle
simulations are tested. Based on these benchmarks, we undertake a generic study of a thrust fault in crust.
We find that lower crustal rheology affects the periodic time of characteristic large earthquake cycles and the
inter-seismic free surface movement. Cratons with a relatively strong lower crust due to lower temperature
remain two peaks in surface uplift profiles around the fault zone for thousands of years after one characteristic
earthquake, which help identify active faults in cratons.

### -> abstract

Visco-elastic-plastic modeling approaches for long-term tectonic deformation assume that
co-seismic fault displacement can be integrated over 1000s–10,000s years (tens of earthquake cycles) with the
appropriate failure law, and that short-timescale fluctuations in the stress field due to individual earthquakes
have no effect on long-term behavior. Models of the earthquake rupture process generally assume that the
tectonic (long-range) stress field or kinematic boundary conditions are steady over the course of multiple
earthquake cycles. This study is aimed to fill the gap between long-term and short-term deformations by
modeling earthquake cycles with the rate-and-state frictional (RSF) relationship in Navier-Stokes equations.
We reproduce benchmarks at the earthquake timescale to demonstrate the effectiveness of our approach. We
then discuss how these high-resolution models degrade if the time-step cannot capture the rupture process
accurately and, from this, infer when it is important to consider coupling of the two timescales and the level of
accuracy required. To build upon these benchmarks, we undertake a generic study of a thrust fault in the crust
with a prescribed geometry. It is found that lower crustal rheology affects the periodic time of characteristic
earthquake cycles and the inter-seismic, free-surface deformation rate. In particular, the relaxation of the
surface of a cratonic region (with a relatively strong lower crust) has a characteristic double-peaked uplift
profile that persists for thousands of years after a major slip event. This pattern might be diagnostic of active
faults in cratonic regions.

### -> scientific keywords

Earthquake Cycles, Navier-Stokes, Viscoelastic-Plasticity, Cratonic Earthquakes

### -> funder

https://ror.org/01h0zpd94, #42030306
https://ror.org/04yx6dh41

### -> model embargo?

_No response_

### -> include model code ?

- [X] yes

### -> model code/inputs DOI

https://doi.org/10.5281/ zenodo.8251145

### -> model code/inputs notes

_No response_

### -> include model output data?

- [X] yes

### -> data creators

Haibin Yang, 0000-0002-8628-3704
Louis Moresi, 0000-0003-3685-174X
Huihui Weng, 0000-0002-2936-2342
Julian Giordani, 0000-0003-4515-9296

### -> model output data DOI

_No response_

### -> model output data notes

_No response_

### -> model output data size

2.8Gb

### -> software framework DOI/URI

https://doi.org/10.5281/zenodo.3975252

### -> software framework source repository

_No response_

### -> name of primary software framework (e.g. Underworld, ASPECT, Badlands, OpenFOAM)

Underworld

### -> software framework authors

_No response_

### -> software & algorithm keywords

Python, Finite element, Particle-in-cell 

### -> computer URI/DOI

_No response_

### -> add landing page image and caption

![Fig5_Compare1100](https://github.com/user-attachments/assets/c15df40c-a8da-4fda-87d5-7b03f24a8408)
Figure 5. Evolution of the stress at the reference point (0, 0, −10 km) (a), maximum slip rate along the entire fault zone (b)
and the adaptive time step used in simulation (c) for the reference model.


### -> add an animation (if relevant)

_No response_

### -> add a graphic abstract figure (if relevant)

_No response_

### -> add a model setup figure (if relevant)

![Fig4_BP5ModelSetup](https://github.com/user-attachments/assets/a30e7fdb-9f7c-4a05-a5c1-29827de61ff8)
Figure 4. The benchmark model BP5 for 3D sequence of earthquakes and
aseismic slip modeling. (a) A vertical planar fault is embedded in the middle
of a homogenous, isotropic half-space with a free surface at z = 0. Fault
behavior is controlled by the rate-and-state friction law. A periodic boundary
condition is applied in y direction. (b) The velocity-weakening (VW) region
(dark and light blue) is located within a transition zone (white), outside of
which is the velocity-strengthening (VS) region (gray). In y and z directions,
the frictional domain and VW region are (L2, L3) and (l, w), respectively. An
initial nucleation zone (dark blue square with a width of w) is designed at the
left end of the VW region.

### -> add a description of your model setup

The BP5 benchmark is first simulated with a reference model size of 96 km (L1) × 100 km (L2) × 30 km
(L3) by 128 × 64 × 64 quadrilateral bilinear elements. Results from the SEAS code comparison platform (https://
strike.scec.org/cvws/seas/) with the mesh resolution of 1000 m are selected for comparison in this study (Table 2).
The stress at a depth of 10 km in the middle point along the fault strike (y = 0) and the maximum slip rate along
the entire fault are tracked for comparison (Figure 5). 0.1 m/s is taken as a threshold of fault slip rate to mark
the earthquake initiation.

### Please provide any feedback on the model submission process?

_No response_