# Code Availability

# hwang_logiacco_2026
Software accompanying the manuscript Hwang, Logiacco et al. 2026: "Microglia shape sensory precision and spatial memory"


## Open-field place cell analysis

Place cell analyses for open-field recordings were performed using the publicly available Information_Metrics package developed by Robson Scheffer Teixeira and colleagues.

Repository:
https://github.com/RobsonSchefferTeixeira/Information_Metrics

The analyses were performed following the tutorial notebook:

https://github.com/RobsonSchefferTeixeira/Information_Metrics/blob/main/notebooks/tutorial_spatial_information_imaging_continuous_1D.ipynb

All underlying functions and dependencies are available within the same public repository.


## Two-photon calcium imaging analysis

ROI extraction and initial fluorescence processing were performed using Suite2p.

Custom Python scripts were used for neuropil correction, baseline estimation, robust noise normalization, event detection, tuned-neuron classification, response quantification, and spatial density analyses.

The analysis pipeline is based on established approaches including neuropil correction, percentile-based baseline estimation, MAD-based robust normalization, kernel density estimation (KDE), and standard calcium-imaging event detection procedures.

Detailed analysis scripts and implementation details are available from the authors upon reasonable request.


## Linear track place cell analysis

Linear track analyses were performed using the methodology and analysis pipeline described in:

"Shuman, T., Aharoni, D., Cai, D.J. et al. Breakdown of spatial coding and interneuron synchronization in epileptic mice. Nat Neurosci 23, 229–238 (2020)".


## Neuropixels electrophysiology analysis

Neuropixels data were processed using custom analysis scripts developed for this study.

Detailed code and implementation information will be provided together with the reviewer-accessible code repository and associated documentation.