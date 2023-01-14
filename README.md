# OpenFOAM tutorials

The OpenFOAM examples available in this repository are:

* Incompressible flow in 2D channel with cavity (icoFoam)
* Bubble rising in axisymmetric domain (interFoam)
* Heat transfer in mixing elbow (buoyantSimpleFoam with Boussinesq assumption, previously known as buoyantBoussinesqSimpleFoam)
* Conjugate heat transfer (chtMultiRegionFoam)
* Steady flow around the propeller (simpleFoam)
* OpenFOAM programming including (icoFoam + energy equation) and Heated cavity
* Stepped spillway (interFoam)
* Simulation of gas flow and speicies transport in non-premixed combustion (reactingFoam)
* Simulation of turbulence in premixed combustion usig LES (XiFoam)
* Wind Flow around building (simpleFoam)
* Particle flow in cyclone (denseParticleFoam, previously known as DPMFoam, MPPICFoam)

The tutorials related to these OpenFOAM examples are gathered in the book entitled **OpenFOAM9 training via problem-solving**.
The book is writen in Persian, and can be accessed via following researchgate link:

http://dx.doi.org/10.13140/RG.2.2.25519.61601


Please cite and refer to the above guidebook, whenever you use this material.


## requirements
There are various methods for installing and utilizing OpenFOAM. However, the recommended approach is to 
install OpenFOAM and required packages on ubuntu LTS versions.

1- install OpenFOAM9

https://openfoam.org/download/9-ubuntu/

2- install swak4Foam

https://openfoamwiki.net/index.php/Installation/swak4Foam/Downloading#swak4Foam_development_version


3- download tutorials via git

`git clone git@github.com:NimaSam/OpenFOAM_tutorials.git` 

in case git is not available in your ubuntu

`sudo apt-get install git`






