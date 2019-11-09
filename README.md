# Context dependent representations of objects and space in the primate hippocampus during virtual navigation
## Roberto A. Gulli, Lyndon R. Duong, Benjamin W. Corrigan, Guillaume Doucet, Sylvain Williams, Stefano Fusi, & Julio C. Martinez-Trujillo

### Nature Neuroscience
DOI: tbd

## Overview

This directory hosts the data that was analyzed and included in Gulli _et al._ Nature Neuroscience (in press). 

For code used to process and analyze this data, please email Roberto Gulli. 


## Example neurons

In **Fig. 1c**, six example neurons are shown with spikes overlaid on trajectories through the virtual reality environment. 

Data from these neurons used to generate these plots can be found in the directory `example_neurons`.


## Spatial information content and spatial firing fields

**Fig. 1d** reports spatial information content for the population of hippocampal neurons recorded in each task. 

The specificity of each neuron’s spatial response map was quantified using spatial information content(31, 53) (Figure 1E). Each neuron’s information content (I; in bits) is defined as

![sic](http://www.sciweavers.org/tex2img.php?eq=I%20%3D%20%5Csum_i%5EL%20P_i%20%5Cfrac%7B%5Clambda_i%7D%7B%5Cbar%7B%5Clambda%7D%7D%20%5Clog_2%20%5Cfrac%7B%5Clambda_i%7D%7B%5Cbar%7B%5Clambda%7D%7D&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)

where _L_ is the total number of pixels, _P<sub>i<sub>_ is the proportion of time spent in the _i<sup>th<sup>_ pixel, and 

![avgfr](http://www.sciweavers.org/tex2img.php?eq=%5Clambda_i&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0) 
  
is the average firing rate for each pixel. 
  
This data can be found for each neuron can be accessed in the directory `firing_rate_maps`.

Note, _normalized_ spatial information content values are reported in the manuscript. These values subtract the mean of permutation-derived null spatial information content values for each neuron. 

## Spatial response fields
**Fig. 2** shows the number of neurons with a significantly elevated firing rate for each pixel of the maze in each task. All data presented in this figure is derived from the significance maps included in the `significance_maps` directory. These data are organized such that data indices correspond with the average firing rate maps of the previous section. 


## Spatial decoding analyses

**Fig. 3** shows the spatial decoding accuracy using both an allocentric and direction-dependent reference frame, using hippocampal data collected while monkeys completed the X-Maze in both tasks.  

Files containing data for these analyses can be found in the `spatial_decoding` directory. 


## Trial type encoding and decoding analyses


**Figs. 4, 5** & **6** 

## More details

### See [hyperlink example](http://www.google.com).

#
<a rel="license" href="https://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">This page</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://robertogulli.com/data" property="cc:attributionName" rel="cc:attributionURL">Roberto Gulli</a> is licensed under a <a rel="license" href="https://creativecommons.org/licenses/by/4.0/legalcode">Creative Commons Attribution 4.0 International License</a>.
