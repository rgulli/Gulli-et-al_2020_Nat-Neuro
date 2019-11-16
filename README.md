# Context dependent representations of objects and space in the primate hippocampus during virtual navigation
## Roberto A. Gulli, Lyndon R. Duong, Benjamin W. Corrigan, Guillaume Doucet, Sylvain Williams, Stefano Fusi, & Julio C. Martinez-Trujillo

### Nature Neuroscience
DOI: 10.1038/s41593-019-0548-3

## Overview

This directory hosts the data that was analyzed and included in Gulli _et al._ Nature Neuroscience (in press). 

## Example neurons

In **Fig. 1c**, six example neurons are shown with spikes overlaid on trajectories through the virtual reality environment. 

Data from these neurons used to generate these plots can be found in the directory `example_neurons`.


## Spatial information content and spatial firing fields

**Fig. 1d** reports spatial information content for the population of hippocampal neurons recorded in each task. 

The specificity of each neuron’s spatial response map was quantified using spatial information content(31, 53) (Figure 1E). Each neuron’s information content (I; in bits) is defined as

<img src="https://latex2image.joeraut.com/output/img-3add55d7ad3f6fed.png" align="center" border="0" alt="I=\sum_i^L P_i \frac{\lambda_i}{\bar{\lambda}}\log_2  \frac{\lambda_i}{\bar{\lambda}}" />

where _L_ is the total number of pixels, _P<sub>i<sub>_ is the proportion of time spent in the _i<sup>th<sup>_ pixel, and <img src="http://www.sciweavers.org/tex2img.php?eq=%5Clambda_i&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0" align="center" border="0" alt="\lambda_i" width="19" height="18" /> is the average firing rate for each pixel. 

Note, _normalized_ spatial information content values are reported in the manuscript. These values subtract the mean of permutation-derived null spatial information content values for each neuron. 


**Fig. 2** shows the number of neurons with a significantly elevated firing rate for each pixel of the maze in each task. 

Data for these analyses can be accessed in the directory `firing_rate_maps`.  

## Spatial decoding analyses

**Fig. 3** shows the spatial decoding accuracy using both an allocentric and direction-dependent reference frame, using hippocampal data collected while monkeys completed the X-Maze in both tasks.  

Files containing data for these analyses can be found in the `spatial_decoding` directory. 


## Associative memory task trial type encoding and decoding analyses

**Figs. 4, 5** & **6** use regression and classification to examine sensory and mnemonic coding for objects and context in hippocampal neurons recorded during the associative memory task. 

All data for these analyses can be accessed in the `AM_trial_type` directory. 

## More details

For more information about these data, code, questions or comments regarding the analyses, or a PDF of the manuscript and supplemental materials, feel free to email me. 


#
<a rel="license" href="https://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">This page</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://robertogulli.com/data" property="cc:attributionName" rel="cc:attributionURL">Roberto Gulli</a> is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by/4.0/legalcode">Creative Commons Attribution 4.0 International License</a>.
