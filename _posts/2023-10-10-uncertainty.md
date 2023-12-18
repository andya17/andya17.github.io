---
title: "Provenance, Error and Uncertainty"
excerpt_separator: "<!--more-->"
categories:
  - Blog
tags:
  - GIS
  - Uncertainty
  - Malcomb et al.
---

In this post, I am discussing questions based on Figure 6.1 of Longley et al. (2008), which is cited below. The prompt for this blog post is as follows:

- `Do you have first-hand knowledge or experience with uncertainty in spatial/geographic research?
- What responsibilities do geographers have with regards to uncertainty in research?
- What strategies might geographers use to fulfill those responsibilities?`


1. Do you have first-hand knowledge or experience with uncertainty in spatial/geographic research?
Yes, I have experienced the concept of uncertainty to some degree in the two GIS classes I have taken previously (Mapping Global Environmental Change and Conservation Planning). An example which comes to mind is from the latter course, in which a main question which I sought to answer on a report was how to best visualize grassland patches in the town of Middlebury which might be used by nesting birds such as the bobolink. Inherent to the work of students in the class was the idea that we could not be on the ground to proof the dimensions of every possible grassland patch which was identified nor could we know for certain whether birds used each possible patch. We were thus working with the uncertainty of whether real-world conditions matched with predictions for grassland patches made using GIS. In the context of Longley et al. (2008), who portray instances of uncertainty in geographic research as belonging to one of a progression of categories, this uncertainty may lie in the third and final realm of "Analysis"; not all grassland patches could be externally validated due to the time constraints of the course. We held that birds would preferentially use grassland patches partly defined by a certain perimeter-area ratio, which itself may be an inexact metric for the problem. The measurements I completed for the report were also founded in the idea that running the code for the report's visualizations required an optimal resolution as well as an optimal radius value to use when passing a kernel over land cover data. The second realm of uncertainty in Longley et al. (2008) – "measurement and reputation" – could thus also be applicable to this example, for the main contribution of my report was to record that different values for these variables produced different results for the number of grassland patches as well as their total area. Using a greater resolution for a land cover raster may carry with it the uncertainty of whether ground conditions are able to be captured to a sufficient degree.


2. What responsibilities do geographers have with regards to uncertainty in research?
At the very least, geographers should document the uncertainty in their research in the discussion section of a paper. Geographers should be taking uncertainty into account in their studies by researching any past work about reducing ambiguity on the topic. Any recommendations which the researchers make should be limited according to the uncertainty in the research. The authors could also note that further work may be needed to clarify remaining uncertainty.


3. What strategies might geographers use to fulfill those responsibilities?
When working on a script, geographers may test different combinations of input variables to see how small changes affect results. It may be beneficial to document this. Before starting an analysis, they should research the information which exists on the topic, especially with respect to other researchers' reports of uncertainty in their own studies. In view of Technical Box 6.3, it is also undoubtedly useful to have more than one researcher attempt an analysis due to the differences in how measurements can be reported. 

Sources of uncertainty in the study by Malcomb et al. (2014) which may relate to the "conception" category from Figure 6.1 in Longley et al. (2008) include the lack of information surrounding the "expert-derived and observed linakges of vulnerability" which gave rise to Malcomb's Figure 2, as well as the exact values for the weights used in Table 2 in the same study. There is also uncertainty in the analysis portion (the third category in Longley et al.) based on the vague wording and definitions for resilience versus adaptive capacity in Figures 3-5.

Longley, P. A., M. F. Goodchild, D. J. Maguire, and D. W. Rhind. 2008. Geographical information systems and science 2nd ed. Chichester: Wiley.

Malcomb, D. W., E. A. Weaver, and A. R. Krakowka. 2014. Vulnerability modeling for sub-Saharan Africa: An operationalized approach in Malawi. Applied Geography 48:17–30. https://doi.org/10.1016/j.apgeog.2014.01.004.