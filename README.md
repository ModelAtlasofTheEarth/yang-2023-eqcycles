# New [M@TE](https://mate.science/)! model: 
 _we have provided a summary of your model as a starting point for the README, feel free to edit_
## Section 1: Summary of your model   

**Model Submitter:**  

Haibin Yang ([0000-0002-8628-3704](https://orcid.org/0000-0002-8628-3704))

**Model Creator(s):**  

- Haibin Yang ([0000-0002-8628-3704](https://orcid.org/0000-0002-8628-3704))  
- Louis-Noel Moresi ([0000-0003-3685-174X](https://orcid.org/0000-0003-3685-174X))  
- Huihui Weng ([0000-0002-2936-2342](https://orcid.org/0000-0002-2936-2342))  
- Julian Giordani ([0000-0003-4515-9296](https://orcid.org/0000-0003-4515-9296))  
  
**Model slug:**  

`yang-2023-eqcycles` 

(this will be the name of the model repository when created) 

**Model name:**  

_Numerical Modeling of Earthquake Cycles Based On Navier-Stokes Equations With Viscoelastic-Plasticity Rheology_  

**License:**  

[Creative Commons Attribution 4.0 International]( https://creativecommons.org/licenses/by/4.0/legalcode.txt)

**Model Category:**  

- model published in study   
- community benchmark   
- forward model   
  
**Model Status:**  

- completed   
  
**Associated Publication title:**  

_[Numerical Modeling of Earthquake Cycles Based On Navier‐Stokes Equations With Viscoelastic‐Plasticity Rheology](http://dx.doi.org/10.1029/2023gc010872)_ 

**Short description:**  

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

**Abstract:**  

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

**Scientific Keywords:**  

- Earthquake Cycles   
- Navier-Stokes   
- Viscoelastic-Plasticity   
- Cratonic Earthquakes   
  
**Funder(s):**  
- National Natural Science Foundation of China (https://ror.org/01h0zpd94)  
- National Computational Infrastructure (https://ror.org/04yx6dh41)  
  
## Section 2: your model code, output data  

**No embargo on model contents requested** 

**Include model code:**   

True 

**Include model output data:**   

True 

## Section 3: software framework and compute details   
**Software Framework DOI/URL:**  

Found software: _[Underworld](https://doi.org/10.5281/zenodo.3975252)_ 

**Name of primary software framework:**  

Underworld 

**Software framework authors:**  
- John Mansour ([0000-0001-5865-1664](https://orcid.org/0000-0001-5865-1664))  
- Julian Giordani ([0000-0003-4515-9296](https://orcid.org/0000-0003-4515-9296))  
- Louis Moresi ([0000-0003-3685-174X](https://orcid.org/0000-0003-3685-174X))  
- Romain Beucher ([0000-0003-3891-5444](https://orcid.org/0000-0003-3891-5444))  
- Owen Kaluza ([0000-0001-6303-5671](https://orcid.org/0000-0001-6303-5671))  
- Mirko Velic   
- Rebecca Farrington ([0000-0002-2594-6965](https://orcid.org/0000-0002-2594-6965))  
- Steve Quenette ([0000-0002-0368-7341](https://orcid.org/0000-0002-0368-7341))  
- Adam Beall ([0000-0002-7182-1864](https://orcid.org/0000-0002-7182-1864))  
  
**Software & algorithm keywords:**  

- Python   
- Finite element   
- Particle-in-cell   
  
## Section 4: web material (for mate.science)   
**Landing page image:**  

Filename: [Fig5_Compare1100.jpg](https://github.com/user-attachments/assets/c15df40c-a8da-4fda-87d5-7b03f24a8408)  
Caption: Figure 5. Evolution of the stress at the reference point (0, 0, −10 km) (a), maximum slip rate along the entire fault zone (b)
and the adaptive time step used in simulation (c) for the reference model.  
  
**Animation:**  

Filename: []()  
  
**Graphic abstract:**  

Filename: []()  
  
**Model setup figure:**  

Filename: [Fig4_BP5ModelSetup.jpg](https://github.com/user-attachments/assets/a30e7fdb-9f7c-4a05-a5c1-29827de61ff8)  
Caption: Figure 4. The benchmark model BP5 for 3D sequence of earthquakes and
aseismic slip modeling. (a) A vertical planar fault is embedded in the middle
of a homogenous, isotropic half-space with a free surface at z = 0. Fault
behavior is controlled by the rate-and-state friction law. A periodic boundary
condition is applied in y direction. (b) The velocity-weakening (VW) region
(dark and light blue) is located within a transition zone (white), outside of
which is the velocity-strengthening (VS) region (gray). In y and z directions,
the frictional domain and VW region are (L2, L3) and (l, w), respectively. An
initial nucleation zone (dark blue square with a width of w) is designed at the
left end of the VW region.  
Description:  The BP5 benchmark is first simulated with a reference model size of 96 km (L1) × 100 km (L2) × 30 km
(L3) by 128 × 64 × 64 quadrilateral bilinear elements. Results from the SEAS code comparison platform (https://
strike.scec.org/cvws/seas/) with the mesh resolution of 1000 m are selected for comparison in this study (Table 2).
The stress at a depth of 10 km in the middle point along the fault strike (y = 0) and the maximum slip rate along
the entire fault are tracked for comparison (Figure 5). 0.1 m/s is taken as a threshold of fault slip rate to mark
the earthquake initiation.

  
