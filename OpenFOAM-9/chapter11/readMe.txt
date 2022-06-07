The DPMFoam solver has solver has been replaced by the more general
denseParticleFoam solver, which supports incompressible flow, including the
effect of the volume fraction of particles on the continuous phase, coupled to
multiple run-time-selectable lagrangian clouds.

To run with a single cloud rename the constant/*CloudProperties file to
constant/cloudProperties.

To run with a multiple clouds create a constant/clouds file with a list of the
names of clouds in it. Each cloud then has a corresponding
constant/<cloudName>Properties file.

In addition, cloud properties files also now require a "type" entry to specify
the type of cloud model used (e.g., thermoCloud, reactingMultiphaseCloud,
collidingCloud, etc ...)
