ANIPH Machine Learning Models

This repository contains the machine learning workflow developed in the ANIPH project for predicting thermal properties of PHBV polymers. Models are developed separately for short-chain-length PHAs (sclPHAs) and medium-chain-length PHAs (mclPHAs).

Each subfolder corresponds to a specific property/material combination and contains:

1) Original dataset (*PHAs.xlsx)

2) Preprocessing notebook (*_data_preprocessing_LM.ipynb)

3) Cleaned dataset (*_LM.csv) Dataset obtained after preprocessing (cleaning, filtering, unit harmonization, removing invalid samples).

4) Final training and deployment on Jaqpot notebook (*_regression_LM.ipynb)

The deployed models on Jaqpot were trained and optimized using Random Forest or XGBoost techniques depending on their performance and tailored to the available experimental data.
