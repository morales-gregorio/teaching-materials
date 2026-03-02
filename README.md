# Computational Neuroscience — Teaching Materials

Open-source practical exercises for an introductory course in computational neuroscience, developed by [Aitor Morales-Gregorio](https://morales-gregorio.github.io).

These materials were created for the MSc course *Introduction to Computational Neuroscience* at Charles University (Prague), but can be used independently in any course covering neural data analysis or computational neuroscience fundamentals.

## Exercises

Each exercise is a self-contained Jupyter notebook, estimated at 2–3 hours of hands-on work. Exercises 1–3 use macaque electrophysiology data from [Chen, Morales-Gregorio et al (2022)](https://doi.org/10.1038/s41597-022-01180-1). Exercise 4 uses marmoset connectome data from [Majka et al (2020)](https://doi.org/10.1038/s41467-020-14858-0). All the necessary data to complete the exercises is found in this repository

| # | Notebook | Topic | Key methods |
|---|----------|-------|-------------|
| 1 | LFP | Spectral analysis of resting state brain data | Power spectrum (FFT, Welch), spectrogram, brain state estimation from alpha power, wavelet transform |
| 2 | Spikes | Spike sorting: finding neurons in brain signals | Signal filtering (Butterworth), threshold detection, waveform extraction, K-means clustering, ISI distributions, dimensionality reduction |
| 3 | Visual Trials | Neuronal responses to visual stimuli | Peri-stimulus rasters, time binning, signal-to-noise ratio, trial-to-trial variability (Fano factor) |
| 4 | Graph Theory | Network analysis with NetworkX | Adjacency matrices, clustering coefficients, shortest paths, degree distributions, marmoset connectome analysis, Watts-Strogatz model |

## Requirements

The exercises are not focused on specific packages, instead use general scientific Python libraries. 

- Python 3.9+
- Jupyter
- NumPy, SciPy, Matplotlib, Pandas
- NetworkX (Exercise 4)
- [Elephant](https://elephant.readthedocs.io) (optional, for wavelet transform in Exercise 1)

## For teachers and independent learners

Solution notebooks are available on request. Please email [aitor.morales-gregorio [at] matfyz.cuni.cz](mailto:aitor.morales-gregorio@matfyz.cuni.cz).

## License

This project is licensed under the [BSD 3-Clause License](LICENSE).