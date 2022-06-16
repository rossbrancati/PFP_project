# PFP_project

Patellofemoral pain syndrome (PFPS) is a common running injury that results in pain in the anterior portion of your knee. For most runners who are diagnosed with PFPS, the pain will eventually subside and they can return back to normal running routines. However, runners who get PFPS are at risk of reinjury. The analysis performed on this dataset containt three groups: a healthy group, a group currently with PFPS (injured), and a group who had recovered from PFPS. Kinetic, kinematic, and electromyography data was collected at the first and 21st minute of a treadmill run. Each stride at each timepoint was independently processed using Visual 3D. This exploratory analysis sought to answer a couple of different research questions: 

1. Will machine learning models accurately classify individuals as healthy, injured, and recovered? 
2. Does the onset of fatigue impact a recovered individuals classification? 

We are currently working on a publication with detailed results on analysis methods. This GitHub repository contains opensource jupyter notebooks written in Python 3.0.

The first notebook titled "pre_processing_notebook.ipynb" walks through steps of importing data, ensemble averaging trials, plotting data, removing noisy signals, clipping some of the variables to only the stance phase, running a principal component analyses, plotting principal components for interpretation purposes, and more. Once the paper is released, we may upload the dataset (TBD). 

The second notebook titled "Logistic_Regression_Machine_Learning.ipynb" contains all the setps used in the machine learning portion of the project. These include classifying injured and healthy runners, using leave one out cross validation to prevent overfitting, determining which features are most important for classifying these two groups, ranking feature importance, classifying recovered runners (as either healthy or injured), and more. 

To run these notebooks, you will need access to the data, and will need to change some file paths within the notebooks. 

