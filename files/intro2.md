# Video Holography


## Introduction

Today, despite many efforts by researchers world-wide, there are no holographic projectors that allow video-rate electronically controlled projection of complex holograms. Optically re-write-able holograms exist, but they are too slow; Acoustically-formed holograms can be switched fast but the image complexity is very limited. We identify the essential roadblock as one that we intend to clear by a breakthrough innovation coming from a combination of electronics, optics and material science.
We propose a radically novel way to make and control holograms, that will be based on the direct, analog, nanometer-resolution and nanosecond-speed control over the local refractive index of a slab waveguide core over several square centimetres. Holograms will be formed by leaky waves evanescent from the waveguide, and controlled by the refractive-index modulation profile in the core. That profile will be controlled and modulated by electrical fields applied with nano-precision through one of the cladding layers of the waveguide. To that end, a novel metamaterial is proposed for this cladding. Also novel driving schemes will be needed to control the new holographic projecting method.
With this combined radical innovation in architecture, materials and driving schemes, it is the goal of this project to fully prove the concept of video-rate electrically-controlled holographic projection. This will be the basis for many future innovations and applications, in domains such as augmented reality, automotive, optical metrology (LIDAR, microscopy, ...), mobile communication, education, safety, etc..., and result in a high economic and social impact.


{numref}`ScalingRoadmap` shows the evolution of hologram demonstrators, both in resolution and speed.

```{figure} ./images/video-holography.jpg
:scale: 100 %
:alt: Scaling Roadmap
:name: ScalingRoadmap

Scaling Roadmap

```


{numref}`SelectedImplementation` shows the selected implementation that has been elaborated in this project. A 500 nm thick metamaterial separates the metal electrodes where the requested hologram is applied from the BTO waveguide. As a consequence, no metal is in the presence of the BTO waveguide, which allows light to propagate in the waveguide without scattering losses. The metamaterial is fabricated using SiN wherein vertical trenches are etched at 100 nm pitch in both directions. These trenches have been filled with InGaZnO that has been engineered such that the dielectric constant carefully matches the dielectric constant of SiN.  This lead to a metamaterial that is completely uniform and has no losses, when it is considered as the optical material that forms the cladding of the waveguide. However, when the same metamaterial is looked at from the electrical perspective, we have conductive channels at a 100 nm pitch that guides the electrical signal from the electrical contacts below to the waveguide above.
As the waveguide material, BTO has been selected. BTO is known to have the highest Pockels effect. This enables us to alter the effective dielectric constant of the waveguide locally at a pitch of 100 nm using relative small electric fields. This dielectric variation forms the hologram that is applied.

```{figure} ./images/video-holography2.jpg
:scale: 100 %
:alt: Selected implementation
:name: SelectedImplementation

Selected implementation 

```

Changing the hologram using the hardware in {numref}`SelectedImplementation` can be obtained by changing the voltages at the bottom electrodes, which can be done reasonably fast, e.g. at 100 Hz rate. This allows also to swap the hologram between 3 subsequent holograms, one for red, one for green and one for blue at video rates. This yields full color video holography.

## Main project results

### Metamaterial development



### High-quality BTO waveguide



## Remaining challenges en further work

The control of the BTO waveguide at 100 nm resolution requires close interaction with the metamaterial. Our simulations (see {cite}`croesSubwavelengthCustomReprogrammable2022`) indicate that when the separation between the BTO and the metamaterial goes beyond 5 nm, the effective control is too low for an efficient demonstrator. Therefor, we targeted an oxide-oxide bonding process yielding an separation below 2 nm. Although other demonstrators of oxide-oxide bonding, also in our lab, have indicated that this should be in reach, the practical between the BTO wafer and the metamaterial wafer has not yet been possible.



## Main funding info

*	Programme Funding: Horizon 2020
*	Sub Programme Area: ERC-2016-ADG
*	Project Reference: 742299
*	From October 1, 2017 to March 31, 2023
*	Budget: EUR 2 499 074
*	Contract type: ERC-ADG
