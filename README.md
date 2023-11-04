# ML_model_for_carotenoid

## Description 
This repository represents the machine learning (ML) scripts used in the publication 
"Building a machine learning model to predict optimal mevalonate pathway gene expression levels for efficient production of a carotenoid in yeast" 

Overall, we used stacking to train the ML model for predicting carotenid production using eight different gene expression levels as input.
We first searched for suitable ML algorithms using the pycaret package, and then constructed a three-layer stacking model with kernel ridges as a meta-model.

All analyses were performed under python version 3.7

## Details of the files in the scripts folder

### Building ensemble ML model.ipynb
This file represents a script on the three-layer stacking model that was ultimately constructed to predict carotenoid productivity in this study.
It can preprocess data, build stacking models, draw parity plots, and predict carotenoid productivity.

### Building ensemble ML model.ipynb
This file represents a script that builds a large number of different ensemble models (voting, boosting, bagging, stacking). This script was used to search for the best ML model.

