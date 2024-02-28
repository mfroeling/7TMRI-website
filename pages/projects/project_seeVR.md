---

layout: page
permalink: /projects/seeVR
header:
  image_fullwidth: "banners/seeVRWM.png"

title: "seeVR"
subheadline: 'A TOOLBOX FOR ANALYZING CEREBRO-VASCULAR REACTIVITY DATA'
teaser: 'CVR mapping, Lag mapping, Dispersion mapping'

images:
  - image_id: 'CVR'
    image_name: 'CVR.gif'
    image_title: 'seeVR in action!'
    image_alt: ''  

tags: 
  - projects
  - grp_soft

---

More information about seeVR can be found on the [seeVR website](https://www.seeVR.nl/). 

### About

`seeVR` is a collection of tools and functions for processing
fMRI data that has been acquired with the aim of understaning the cerebrovascular reactivity response.
These can include data acquired using physiological stimuli (both CO2 and O2) or without as in the 
case of resting-state CVR. In addition to mapping hemodynamic responses, seeVR also includes data
pre-processing tools for de-noising, nuisance signal regression and spatial smoothing as well as 
image registration. The toolbox is developed using [Matlab](https://nl.mathworks.com/products/matlab.html), and 
its primary goal is to facilitate fast, advanced processing of CVR data. All code is available for download
at [Github](https://github.com/abhogal-lab/seeVR).

{% include page-image im_id = 'CVR'%}


### Referencing

If you use any CVR functionality for your work (or any derivatives based on the seeVR toolbox) please cite 
the following paper:

Medullary vein architecture modulates the white matter BOLD cerebrovascular reactivity signal 
response to CO2: observations from high-resolution T2* weighted imaging at 7T, AA Bhogal
Neuroimage, 2021, [link](https://doi.org/10.1016/j.neuroimage.2021.118771)

and/or

Alex A. Bhogal. (2021). abhogal-lab/seeVR: Current version. [Zenodo](https://doi.org/10.5281/zenodo.5283595)




