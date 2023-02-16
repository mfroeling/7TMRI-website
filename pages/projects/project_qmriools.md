---

layout: page
permalink: /projects/qmritools
header:
  image_fullwidth: "software.png"

title: "QMRITools"
subheadline: 'Analysis of quantitative magnetic resonance imaging data'
teaser: 'Diffusion, Dixon and EPG T2-mapping'

images:
  - image_id: 'qmritools'
    image_name: 'QMRITools.png'
    image_title: 'applications of QMRITools'
    image_alt: ''  

tags: 
  - projects
  - grp_soft

---

More information about QMRITools can be found on the [QMRITools website](https://www.qmritools.com/). 

### About

`QMRITools` is a collection of tools and functions for processing
quantitative MRI data. The toolbox is developed for the [Wolfram
language](https://www.wolfram.com/language/) and maintained using
[Wolfram workbench](https://www.wolfram.com/workbench/) for
[eclipse](https://www.eclipse.org/) and runs in the latest version of
[Wolfram Mathematica](http://www.wolfram.com/mathematica/). The toolbox does not provide a GUI and its
primary goal is to allow for fast batch data processing, and
facilitate development and prototyping of new functions. The core of the
toolbox contains various functions for data manipulation and restructuring.

{% include page-image im_id = 'qmritools'%}

The toolbox was developed mostly in the context of quantitative muscle
([Froeling et al. 2012](https://onlinelibrary.wiley.com/doi/10.1002/jmri.23608){:target="_blank"}), nerve and cardiac magnetic resonance imaging. The library of functions grows along with the research it is
used for and started as a toolbox to analyze DWI data of muscle. Since
then it has grown to include many other features such as cardiac
analysis (tagging and T1 mapping), dixon reconstruction, EPG modeling
and fitting, j-coupling simulations and more. It currently contains over
450 custom functions (over 30.000 lines of code) complete with more than 750
documentation pages and demonstrations for each toolbox.

### Referencing

When using the toolbox please cite one of the following references:

1.  Froeling M: *QMRTools: a Mathematica toolbox for quantitative MRI
    analysis*. J Open Source Softw 2019; 4:1204.
    [link](https://joss.theoj.org/papers/ef8bfb6c31499845d353b6a5af0d6300){:target="_blank"}
2.  Froeling M, et al.: *Reproducibility of diffusion tensor imaging in
    human forearm muscles at 3.0 T in a clinical setting*. Magn Reson Med
    2010; 64:1182-1190.
    [link](https://onlinelibrary.wiley.com/doi/full/10.1002/mrm.22477){:target="_blank"}
3.  Froeling M, et al.: *Diffusion-tensor MRI reveals the complex muscle
    architecture of the human forearm*. J Magn Reson Imaging 2012;
    36:237-248.
    [link](https://onlinelibrary.wiley.com/doi/10.1002/jmri.23608){:target="_blank"}
4.  Schlaffke L, et al.: *Multi‐center evaluation of stability and reproducibility of 
	quantitative MRI measures in healthy calf muscles*. NMR Biomed. 2019;32:e4119
	[link](https://onlinelibrary.wiley.com/doi/full/10.1002/nbm.4119){:target="_blank"}



