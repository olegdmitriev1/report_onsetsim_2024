# onsetsim_dissertation_2024
Repository for code and files used for 2024 onsetsim dissertation, University of Glasgow, MSc Brain Sciences

20_participants_sim.Rmd - group simulation of 20 participants with median onsets used as group estimates.

appendix.Rmd - file containing the figures and explanations for the figures included in the abstract.

example_participant_plots.Rmd - code to make a figure showing onset estimates from each method (cluster-sum, FDR, BinSeg, mcp, PELT, cp3o_delta) on an example simulated participant time course (seed 666).

pelt_analysis.Rmd - analysis of different penalty multiplier values for PELT and how they affect the distribution of onset estimates. 

real_data.Rmd - application of cluster-sum, BinSeg, PELT, mcp and cp3o_delta to EEG participant data from Bieniek et al., (2016). Methods were applied to 120 participant time courses from session 1 and then test-retest reliability of methods was assessed by analysing time courses of 74 participants that took part in the second retest session. 

real_data_prior_test.Rmd - code to create onset distributions comparing wider priors for mcp. It was found that using wider priors did not have an impact on the final comparison between methods. 

single_participant_sim.Rmd - simulation of a single EEG participant with randomised noise with 10,000 iterations. Onset estimates as obtained by each method were plotted to show distribution. 

vary_n_sim.Rmd - simulation of a single EEG participant but where the number of trials is varied from 20 to 150. This was done to check how chaning the number of trials affects bias, mean absolute error, variance and % of underestimations for each method. 
