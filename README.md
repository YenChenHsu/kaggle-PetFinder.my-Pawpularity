# Introduction
This Kaggle project for PetFinder.my, a Malaysian animal welfare platform, aims to use AI to enhance pet photo appeal on their website, thereby increasing adoption rates for stray and shelter animals. The approach involved developing a deep learning solution using Convolutional Neural Networks (CNNs) to predict "pawpularity score" for pets.

# Data Set
##### Data Source [https://www.kaggle.com/competitions/petfinder-pawpularity-score/data]
The data set contains training (9912) and test (6800) image files and CSV files of pets, the CSV contains the metadata of the images: 12 binary variables showing the image features (i.e. whether the pet has eyes/ face/ action.. etc) and 1 Pawpularity score column. Our objective is to predict the Pawpularity score for respective images.

# Technical Document Guide
Please refer to annotated write-up document for the overall technical solution, the detailed code can be found in "Pawpularity_Code". Our annotated write-up includes the description of exploratory data analysis, data pre-processing, model-building process, and performance summary. 

# Performance Summary
This project use Root Mean Square Error (RMSE) score as performance evaluation, out of all models we've implemented, the best model reports a RMSE of 20.51.
<img width="567" alt="截圖 2024-01-14 下午2 44 16" src="https://github.com/YenChenHsu/kaggle-PetFinder.my-Pawpularity/assets/57134574/7fe8cecc-afce-43c2-9453-e01c75932faf">

# Future Recommendation
To further optimize the model, we come up with several improvement directions:
1. The stacking method is worth trying to improve RSME Performance
2. A better way to use the pre-trained model would be setting trainable = False at the initial stage to fix the good parameters in the pre-trained model and let the hidden layers learn the parameters.

# Link
Video [https://www.youtube.com/watch?v=dlYdpkSYzHo]
Kaggle Competition [https://www.kaggle.com/competitions/petfinder-pawpularity-score]

# Contributor
Guoquan Lin, Otto Gaulke, Yen Chen Hsu, Wei-Chun Chang, Joyce Wu
