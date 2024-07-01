# MACSS
## MACSS: machine learning applied to chemometric spectral analysis

Author: Dr. Rodrigo Cupertino Bernardes [LinkedIn](https://www.linkedin.com/in/rodrigo-cupertino-bernardes/)

## Overview
This platform is associated with the scientific study titled "AI-driven detection of pesticide contamination in bees using reflectance profiling." The study explores the application of hyperspectral reflectance data and machine learning models to identify pesticide contamination in bee carcasses.

The dataset used in this study is available on the Zenodo platform: [https://doi.org/10.5281/zenodo.11643453](https://doi.org/10.5281/zenodo.11643453)


**MACSS** (Machine Learning Applied to Chemometric Spectral Analysis) is an platform that leverages machine learning techniques to analyze chemometric spectral data from technologies such as spectrometers.
The MACSS graphical interface has tabs, including "Sample Identification," where users can identify new samples based on a pre-trained artificial intelligence model designed to detect pesticide contamination in bees using reflectance spectroscopy. Users can also upload their own models to identify new samples.

In the "Training" tab, users can train their own models by uploading a database (in .txt format) with samples and their respective categories. The platform offers data transformation options, such as normalization and derivatives, as well as different machine learning models, including linear discriminant analysis, partial least squares discriminant analysis, support vector machines, and random forests. After training, performance metrics and visualizations, such as confusion matrices, are presented, and the trained model can be downloaded for use in identifying new samples.

MACSS optimizes the identification and characterization of samples based on their spectral signatures, making it useful in areas such as environmental monitoring, agricultural research, and industrial quality control.


## Running the Application
### To run the application locally:

- Make sure you have R installed on your machine.
- Execute the script run_macss_app.R.
- The application will open in your default web browser.
#### System Requirements
R version 4.4.0 or higher is recommended.
### Web Application
The application is also available online as a web app at [https://macsstat.shinyapps.io/macss/](https://macsstat.shinyapps.io/macss/). However, running it locally is recommended due to the heavy computational load of the AI models, which may cause disconnections on the web server due to insufficient RAM.
