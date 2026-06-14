# Computational_Astrobiology

## Project header and title
Computational-Astrobiology-Project-Technosignatures-PSG-to-PLATO
From Planetary Spectra to PLATO-like Observables: Biosignatures and Industrial Pollution in Broadband Photometry

## Summary
This project studies whether atmospheric signatures relevant to biosignatures and possible technosignatures can remain detectable after high-resolution planetary spectra are compressed into PLATO-like broadband photometric observables. The project uses NASA PSG https://psg.gsfc.nasa.gov/ to generate synthetic planetary spectra and then applies PLATO throughput convolution to test how much information survives the transition from spectroscopy to broadband photometry. PSG is a radiative-transfer tool for generating planetary spectra, while PLATO is a visible-band photometric mission rather than a spectroscopic atmosphere mission. Main idea The student will build a forward-modeling pipeline:

Generate synthetic exoplanet spectra with NASA Planetary Spectrum Generator (PSG).

Define several atmospheric scenarios, including Earth-like, biosignature-enhanced, and pollution-enhanced cases.

Convolve the spectra with a PLATO-like throughput curve.

Convert the convolved spectra into broadband observables.

Test whether different atmosphere classes remain distinguishable after convolution.

Quantify how much spectral information is lost.

The project is not a direct gas-retrieval study for PLATO. Instead, it is a detectability and information-loss study, which is scientifically much more appropriate for broadband photometry.

### Instructions to run ("open Astrobiology-Project-FINAL-VarunaDeopersad.ipynb and Restart & Run All").
Files needed to run the notebook successfully are as follows:

psg_rad-EarthPrototype.txt
psg_tel-EarthPrototype.txt
psg_trn-EarthPrototype.txt
psg_trn-40000ppm-CO2.txt
psg_trn-10000ppmCH4.txt
psg_trn-Cloudy-water.txt
psg_trn-c2f6.txt
psg_trn-C3F8.txt
psg_trn-CF4.txt'
