Sleep-EDF EEG Signal Analysis
This repository contains Python code for analyzing EEG signals from the Sleep-EDF database. The analysis includes visualizing individual channels, computing band powers, and performing channel selection.
Introduction
The Sleep-EDF database is a valuable resource for studying sleep patterns through EEG signals. This repository provides Python code using the PyEDFlib library for reading and analyzing EEG data. The analysis includes visualizing individual channels, computing band powers, and performing channel selection based on user preferences.

Dependencies
Make sure you have the following dependencies installed before running the code:
PyEDFlib
Matplotlib
Numpy

Visualizing Individual Channels
The script visualize_channels.py reads an EDF file and plots each EEG channel over time. Adjust the file path to your specific EDF file.

Computing Band Powers
The script compute_band_powers.py calculates the power spectral density of each EEG channel and computes band powers in specified frequency ranges.

Channel Selection
The script select_channels.py allows you to choose specific channels from the original EDF file and create a new EDF file with only the selected channels.

subbands: Dividing selected channels into 5 subbands.
    Delta 
    Theta 
    Alpha 
    Beta 
    Gamma
    
Feature Extraction:Below features for each channel or selected channels.
  Mean
  Variance
  Skewness
  Kurtosis
  
Acknowledgments
Sleep-EDF Database: Link to the Sleep-EDF Database
PyEDFlib: PyEDFlib GitHub Repository
