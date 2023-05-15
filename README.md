University of Aberdeen - Aleksandra Nenkova
# Exploration of Soybean Yield Forecasting with Transformers
This repository host the code for a final project done as part of course requirements in Level 4 at University Of Aberdeen

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
  1. Full dataset forecasting: using full dataset with no changes.
  2. Per-state forecasting: separates the dataset into states.
  3. Non-outlier dataset forecasting: excl. S. Dakota, N. Dakota and Kansas data.
  4. Predicting outlier yield with non-outlier-trained models: predicts yield from outlier states
using the pretrained models from the previous experiment (3).
  5. Sorted dataset forecasting: uses a chronologically sorted version of the full dataset.
In order to run the notebook ensure all requirements are met as described in the Maintenance
manual below and follow the steps as outlined:
  • Navigate to the folder containing SoybeanForecastingPipeline.ipynb
  • Right click folder and select Open in Terminal
  • Type jupyter notebook SoybeanForecastingPipeline.ipynb to open the file
(Alternatively, the recommended way to open the file is using VSCode and its Jupyter Notebook
extension as it makes navigating easier by providing an outline of the notebook.)
