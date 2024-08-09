University of Aberdeen - Aleksandra Nenkova
# Exploration of Soybean Yield Forecasting with Transformers
This repository host the code for a final project done as part of course requirements in Level 4 at University Of Aberdeen

## Pred_state() issues fix:
Small issue was caught with the submitted version of the Jupyter notebook. In order to run the 2nd experiment please download the code from GitHub or do the following change to the pred_state(). No further changes are required and notebook should run as intended.


![image](https://github.com/AlexaN-00/soybean_forecasting_dissertation/assets/55953609/bd7e9d14-6e04-4b73-85a3-fc2f751778b5)

## Requirements 
### Hardware requirements:

  • 64-bit processor
  
  • 4GB RAM or higher
  
  • 10GB of disk space
### Software dependencies:

  • Python 3.8 or higher
  
  • Jupyter Notebook
  
  • Scikit-learn
  
  • Pandas
  
  • Numpy
  
  • Matplotlib
  
  • XGBoost
  
  • TensorFlow
  
  • Keras
  
  • for all dependencies check requirements.txt
  
  ## Usage 
  
  The main file SoybeanForecastingPipeline.ipynb, contains four models which can be used
for experimentation and prediction of soybean yield with the supplied dataset. Additionally there
are five experiments that can be run:

  1. Full dataset forecasting: using full dataset with no changes
  2. Per-state forecasting: separates the dataset into states.
  3. Non-outlier dataset forecasting: excl. S. Dakota, N. Dakota and Kansas data.
  4.  Predicting outlier yield with non-outlier-trained models: predicts yield from outlier states
using the pretrained models from the previous experiment (3).
  5. Sorted dataset forecasting: uses a chronologically sorted version of the full dataset.

In order to run the notebook ensure all requirements are met as described in the Maintenance
manual below and follow the steps as outlined:

  • Navigate to the folder containing SoybeanForecastingPipeline.ipynb
  
  • Right click folder and select Open in Terminal
  
  • Type jupyter notebook SoybeanForecastingPipeline.ipynb to open the file
  
(Alternatively, the recommended way to open the file is using VSCode and its Jupyter Notebook
extension as it makes navigating easier by providing an outline of the notebook.)
