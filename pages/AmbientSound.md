---
layout: page
title: Ambient Sound Propagation
description: Project webpage of ambient sound propagation
---

# Ambient Sound Propagation

[Zechen Zhang](zechenz.github.io), Cornell University  
[Nikunj Raghuvanshi](www.nikunjr.com), Microsoft Research  
[John Snyder](https://www.microsoft.com/en-us/research/people/johnsny/), Microsoft Research  
[Steve Marschner](www.cs.cornell.edu/~srm/), Cornell University  

---
<img src="https://raw.githubusercontent.com/ZechenZ/zechenz.github.io/master/_figure/img_SASIA2018.PNG" alt="teaser" width="500"/>

## Abstract
Ambient sounds arise from a massive superposition of chaotic events distributed over a large area or volume, such as waves breaking on a beach or rain hitting the ground. The directionality and loudness of these sounds as they propagate in complex 3D scenes vary with listener location, providing cues that distinguish indoors from outdoors and reveal portals and occluders. We show that ambient sources can be approximated using an ideal notion of spatio-temporal incoherence and develop a lightweight technique to capture their global propagation effects. Our approach precomputes a single FDTD simulation using a sustained source signal whose phase is randomized over frequency and source extent. It then extracts a spherical harmonic encoding of the resulting steady-state distribution of power over direction and position in the scene using an efficient flux density formulation. The resulting parameter fields are smooth and compressible, requiring only a few MB of memory per extended source. We also present a fast binaural rendering technique that exploits phase incoherence to reduce filtering cost.

---

## Downloads

[Paper](https://raw.githubusercontent.com/ZechenZ/zechenz.github.io/master/pages/Paper/SAsia-2018-ambient2.pdf)

---

## Video

<iframe src="https://player.vimeo.com/video/292495561" width="640" height="360" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>

---

## Bibtex

@article{ Zhang2018Ambient,  
> > >title={Ambient Sound Propagation},  
> > >    author={Zhang, Zechen and Raghuvanshi, Nikunj and Snyder, John and Marschner, Steve},  
> > >    journal={ACM Trans. Graph.},  
> > >    volume={37},  
> > >    number={6},  
> > >    year={2018}, 
 
}