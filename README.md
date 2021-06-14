# Volcanic Activity Detection
Authors 
Myles Mason, John Wenskovitch, D. Sarah Stamps, Joshua Robert Jones, Mike Dye

# Abstract

This Jupyter notebook aims to explore methods towards characterizing noise in positioning data and eventually predicting volcanic activity for Ol Doinyo Lengai (an active volcano in Tanzania) with machine learning. Machine learning is a powerful tool that enables the automatization of complex mathematical and analytical models. One specific algorithm tested in this notebook is linear regression, which aims to fit a linear model with coefficients to minimize the residual sum of squares between the observed components in the dataset and the components predicted by the linear approximation. In the case of this Jupyter notebook, the components are height, latitude, and longitude. The predicted component values are the next heights. This project uses Global Navigation Satellite System  (GNSS) data from the EarthCube CHORDS portal TZVOLCANO, which is the online interface for obtaining open-access real-time positioning data collected around Ol Doinyo Lengai (http://tzvolcano.chordsrt.com). The data from CHORDS are imported as a JSON file and have four main columns that are of interest to this project that are height (m), longitude (decimal degrees), latitude (decimal degrees), and time (converted to seconds). The columns of interest are imported into the Jupyter notebook as measurements_height, measurement_lon, measurement_lat, and time, respectively. These data represent the positions of GNSS stations around Ol Doinyo Lengai. The notebook is developed in Python 3. The main libraries that are used throughout this notebook are pandas, numpy, matplotlib, and scikit-learn. We use this notebook to explore a variety of techniques available in the scikit-learn library in addition to linear regression, such as support vector machine, and k-nearest neighbors, to detect anomalous signals from the GNSS data obtained from the TZVOLCANO EarthCube CHORDS portal.



[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/mylesm19/Volcaninc_Activity_Detection/HEAD)



Required Packages
## six==1.15.0
## pandas==1.1.3
## numpy==1.19.2
## matplotlib==3.3.2
## seaborn==0.11.0
## scikit-learn==0.23.2

