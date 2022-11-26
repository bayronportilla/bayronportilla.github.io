---
layout: page
title: A thermochemical model for PDS 70
description:
img:
importance: 2
category: PhD
---

ALMA revealed several rotational features in the sub-mm spectrum towards PDS 70. Those
features are associated to different molecules in the coldest
regions of the disk. Since the gas phase is the dominant component, its distribution across
the disk links to some of the most its most promiment features, like
the planets in the cavity, and the location of the pressure bump at the outer
dust ring. For this same reason, the gas distribution is a key parameter on which
multiple theoretical predictions have been built upon. A physically
motivated model for the gas phase is needed to understand those observations and test
theoretical predictions. Our goal is to develop a thermochemical model to explain the
gas phase observations from PDDS 70 and use it to estimate the mass of the
gap carving planets. This experiment represents a test to theoretical ideas about
giant planet formation in protoplanetary disks.  

Using ALMA data for the CO molecule and its isotopologues from the PDS 70 disk (CO J=2-1, 13CO J=2-1,
  and C18O J=2-1), we construct a thermochemical model building upon
the model for the continuum introduced in [project 1](/projects/1_project/). I use the
Protoplanetary Disk Model code (ProDiMo) for which a dedicated translation strategy from
MCMax3D was designed and implemented. The first part of the modelling consisted in
a parametric exploration of the spacially unresolved inner disk that is only observed in the optically
thick tracer. Each simualtion is a self-consistent solution to the physical state of the system
that iterates over the continuum radiative transfer, the chemistry, and the heating-cooling
balance. The, the ray-tracing module is called to create the images. Those modelled
data cubes were postproceded with CASA and the packages GoFish and ProDiMopy to
obtain the azimuthally averaged birthness distribution of each transition which
was compared to the observations. Once the inner disk was fitted, we used an iterative
procedure informed by a simple analyical model for the C18O abundance to fit the signal
from the spatially resolved outer disk.

We found a gas-to-dust ratio profile that disfavors the common assumptions of a constant
value. In fact, the gas-to-dust ratio values span two orders of magnitude across
the 130 au simulated in our work. Our model suggest a peak value of gas column density
of ~0.13 g/cm2 located at ~75 au. The minimum value of the gas column density (~0.003 g/cm2)
happens matches the location of the planet PDS 70 b. Unlike the dust phase, the inner
and outer edges of the gas cavity are not sharp. The gas temperature profile points
towards a characteristic value of xxxx K at the bottom of the cavity. Finally, coupling
our model with the theoretical prediction by Duffel and Dong 2015, we predict a
value for the mass of each planet of ~ 2 Mjup which is consistent with the values
obtained by Wang et al 2021 using infrared spectroscopy.     

This project is in the final correction phase and I expect to submit the paper by the end of 2022.
Stay tuned for the manuscript!  
