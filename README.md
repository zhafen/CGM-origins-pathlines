# The Origins of the CGM Visualized

This repository contains [online interactive visualizations of the CGM](https://zhafen.github.io/CGM-origins), using data from Hafen et al. (2018). These visualizations were developed using [Firefly](https://github.com/ageller/Firefly). [A complimentary visualization is available here.](https://zhafen.github.io/CGM-origins-pathlines)

When you first start the visualization you can select a simulation and redshift you would like to view. The simulations available were created as part of the [FIRE project](https://fire.northwestern.edu). Two redshifts are available per simulation: `lowz` and `highz` corresponding to z=0.25 and z=2 respectively.

The loaded visualization will display ~1e5 particles at the specified redshift and sampled out to within the virial radius, as described in Hafen et al. 2018. Each particle is colored according to their origin:

1. IGM Accretion (blue) - material that has either never been inside a galaxy or inside a galaxy only a short time.
2. Wind (green) - material that was ejected from the central galaxy.
3. Satellite ISM (red) - material that is in a galaxy other than the central galaxy.
4. Satellite Wind (orange) - material that was ejected from a satellite galaxy.

There are a few additional things to note

* All distances are in proper kpc relative to the central galaxy.
* A white ruler (100 kpc on a side with 1 kpc spacing between points) can be toggled on and off.
* A secondary ruler points along the total angular momentum of the stars and is 50 kpc long, with 1 kpc spacing between points. This ruler is accompanied by a disk with a radius corresponding to the galaxy radius, defined as four times the stellar half mass radius.
* The position of stars at the specified redshift are shown in yellow.
* Clicking on the downward arrow next to a classification allows one to filter the data according to a variety of options.
