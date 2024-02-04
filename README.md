1D numerical model of ocean surface boundary layer (OSBL) current velocity at a given depth z for varying eddy diffusivity parameter K. 

This is done under the mentorship of Dr. Marcelo Chamecki at UCLA. This work builds off of his paper found [here]([url](https://journals.ametsoc.org/view/journals/phoc/51/5/JPO-D-20-0250.1.xml)https://journals.ametsoc.org/view/journals/phoc/51/5/JPO-D-20-0250.1.xml).
RK3 is used to numerically approximate velocity vectors u and v at each point in z, which consists of a series of evenly-spaced nodes valued from 1 to -100, where 1 is a ghost node for modeling purposes and -100 corresponds to a depths of 100m below the ocean surface.
The goal of this project is to model ocean current velocities to better understand the trajectory of particles in the OSBL of varying sizes, such as from an oil spill. Current LES simulations approach this answer but are computationally expensive, so this model is developed using the LES results as a reference with the aim to produce results more quickly.

Author: Sierra Stevenson, UCLA Atmospheric and Oceanic Sciences C.O. 2024
