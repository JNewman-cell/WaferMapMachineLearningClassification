# WaferMapMachineLearningClassification

In this code I used machine learning to create a model that classified real wafer map data with >80% accuracy using the WM-811K Wafer Map Dataset. I used feature extraction and creation so the Decision Tree classifier from SKLearn was able to distinguish the unique characteristics of each failure type. I used five categories of failure classification, Center, Edge-Loc, Donut, Near-Full, and Scratch.

## Preparing the Data

This dataset came without any features that could contribute to the classification of the wafer maps. Therefore, I used the skimage measure and morphology classes to add features to the maps, such as salient region and outer ring yield. This allowed me to successfully classify each wafer map and predict wafer maps.

## Final Results
I created an overall accuracy and per class accuracy functions to identify which classes were incorrectly classified. Using these functions and confusion matrices, I further tweaked my model so that the accuracy improved. 
