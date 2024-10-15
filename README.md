# Project Title: Transit Method for Exoplanet Detection

## Project Overview:
This project focuses on detecting exoplanets using NASA's Transiting Exoplanet Survey Satellite (TESS) data. By analyzing light curves from stars, we identify periodic dips in brightness indicative of exoplanets transiting their host stars. This technique allows us to measure various parameters of these distant worlds, including their size, orbital period, and potential habitability.

Leveraging tools like the Lightkurve Python library and the Box Least Squares (BLS) algorithm, we processed time-series data from TESS and identified several promising exoplanet candidates, including TIC 44792534, TIC 460205581, and TIC 207468071.

## My Role:
For this project, I was responsible for the following:

Writing Python code to automate the detection of transits using the BLS algorithm.
Processing and normalizing light curves to remove noise and extract clean signals.
Implementing statistical techniques such as sigma-clipping and bootstrap analysis to reduce false positives and ensure accurate results.
Analyzing the detected transits, estimating parameters like planetary radius, equilibrium temperature, and orbital periods.
Visualizing the light curve data and phase-folded transits to validate exoplanet candidates.

## Key Tools and Techniques:
Lightkurve: For light curve analysis and data visualization.
Box Least Squares (BLS) algorithm: For detecting periodic dips in brightness due to planetary transits.
Data Normalization: To scale brightness values for consistency across datasets.
Transit Detection and Phase Folding: To enhance the visibility of transit signals and estimate planetary parameters.

## Project Goals:
Detect and confirm exoplanet candidates from TESS data.
Analyze the characteristics of detected planets, such as size and orbital period.
Provide insights into the diversity of planetary systems and their potential habitability.
