# directional_connectome
## Introduction
The idea of this project is to use directional connectome information from tracing studies of the macaque brain to generate a directed version of the human structural connectome. To do so, I have created a mapping of human brain regions in the Desikan-Killiany atlas (DK; Desikan et al., 2006) to analagous regions of the macaque brain in the RM atlas (Kotter and Wanke, 2005) using anatomical and functional similarities derived from literature search.
Both the RM and DK atlases are based on gross anatomical features (gyri and sulci). Thus, region mappings were first assessed visually by warping/ aligning the two atlases using analagous anatomical features (see image below) and then confirmed if they shared functions as confirmed by literature search and/or a label in Brodmann's human parcellation (http://cocomac.g-node.org/downloads/regionalmap.pdf)
![Comparison of RM and DK atlases](https://github.com/jenncummings/directional_connectome/blob/ccf82c1372879897067e965f5caf136f8f09afee/desikan_to_RM.png)
## The pitfall
CoCoMac data cannot actually be used to infer directionality of connections between brain regions. In order to confirm that a connection is directional, tracers would have to be injected into both source and target regions and the amount of tracer present in both source and target would have to be reliably quantified to deduce a ratio. Furthermore, in the CoCoMac database, information is not reliably available as to whether anterograde or retrograde tracers were used for a given study. Thus, all that can be determined from cocomac data "is whether each connection of interest is present, absent, or unknown" (Blumenfeld et al., 2014). 
## References
Bakker, Rembrandt, Thomas Wachtler, and Markus Diesmann. "CoCoMac 2.0 and the future of tract-tracing databases." Frontiers in neuroinformatics 6 (2012): 30.  

Blumenfeld, Robert S., et al. "CoCoTools: Open-source software for building connectomes using the CoCoMac anatomical database." Journal of cognitive neuroscience 26.4 (2014): 722-745.  

Desikan, Rahul S., et al. "An automated labeling system for subdividing the human cerebral cortex on MRI scans into gyral based regions of interest." Neuroimage 31.3 (2006): 968-980.  

K??tter, Rolf, and Egon Wanke. "Mapping brains without coordinates." Philosophical Transactions of the Royal Society B: Biological Sciences 360.1456 (2005): 751-766.
