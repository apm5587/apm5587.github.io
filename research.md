---
layout: page
title: Research
---

I am broadly interested in galaxy formation, evolution, and how galaxies relate to their dark matter halos. I enjoy using data science to learn new things about our Universe. I present short summaries of my research projects below.

## Lyman-alpha Emitting Galaxies

Update: the ApJ submitted paper can be found <a href="../assets/documents/McCarron_manuscript_v20220126.pdf">here</a>.

Leveraging the HETDEX dataset, I studied the stellar population properties of a sample of Lyman-alpha emitting galaxies (LAEs) between redshifts 1.9<z<3.5. I used spectral energy distribution (SED) fitting techniques to constrain the posterior distributions for galaxies' masses, star formation rates, dust contents, and more within a Bayesian framework. Such a technique explores the full galaxy parameter space using a Markov chain Monte Carlo method to find which parameters produce a spectral model best reflected by the observed data (in this case, from the Hubble Space Telescope). The pictures below show a model fit to the data as well as a "corner" plot showing the posterior distributions and their interdependencies. 

 <img src="../assets/img/research/sedfit_10388.png" width="600" class="center"  />
 <center> <span style="font-size:0.8em; font-style:italic;"> Figure: An example SED fit for a high-redshift LAE  </span> </center>
 
<img src="../assets/img/research/cornerplot_10388.png" width="600" class="center" />
<center> <span style="font-size:0.8em; font-style:italic;"> Figure: A corner plot showing the posterior probability distributions for galaxy properties along the main daigonal with covariances visualized in the lower triangle. </span> </center>

My goal was to uncover exactly how these galaxy properties relate to the strength of Ly&alpha; emission, knowledge that could be invaluable for measuring the amount of neutral hydrogen in the epoch of reionization. We found strong correlations with mass and SFR, and, surprisingly, no correlation with dust (A<sub>V</sub>). 

<img src="../assets/img/research/six_ew_correlations.png" width="600" class="center" />
<center> <span style="font-size:0.8em; font-style:italic;"> Figure: Correlations between galaxy properties and Ly&alpha; emission strength. </span> </center>
