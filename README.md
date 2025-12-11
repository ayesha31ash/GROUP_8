# GROUP 8: Multimodal Skin-Lesion Classification (Derm7pt)



 H00505014 	Anam Ayyub 

 H00498947  Ayesha Syed Mohammad

 H00519518	Nandini Petli

 H00363811	Prianshu Rajput

 H00521656  Yogesh Lachman Wadhwani


### Datasets can be found under the 'Dataset' folder in the repo




## 1. Runnable Files for Results

a.  [01_EDA.ipynb](notebooks/01_EDA.ipynb) for Initial clean up and exploration, cleaning and visualization

b.  [02_Baselines.ipynb](notebooks/02_Baselines.ipynb) for traditional ML models with tuning and visualizations

c.  [Image_Implementation.ipynb](notebooks/Image_Implementation.ipynb) for CNN + Fusion implementation

Extras:

a. Detailed decision trees process in [03_DecisionTree_Analysis.ipynb](notebooks/03_DecisionTree_Analysis.ipynb)

b. [04_CNN_Sandbox_Images.ipynb](notebooks/04_CNN_Sandbox_Images.ipynb) and [05_Final_CNN_Model.ipynb](notebooks/05_Final_CNN_Model.ipynb) files try a variety of techniques to get more results




## 2. Extra Information

- Worthy correlations are outputted to output.txt for visualizing.
- Cleaned DataFrame without 'diagnosis' column ready for classifying in sampling.csv file.
- Metrics used for files: Macro F1, ROC-AUC, sensitivity/specificity.

## 3. Required libraries

- os
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- lightgbm
- sklearn
- imblearn
- tensorflow
- torch
- torchvision
- PIL
- tqdm
- warnings

##  Project Presentation
**Skin_Lesion_Classification_FINAL_Presentation.pdf**  
This file contains the final slides for the Derm7PT project.


