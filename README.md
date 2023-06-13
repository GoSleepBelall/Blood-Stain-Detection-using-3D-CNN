# Blood Stain Identification using 3D CNN
Blood Stain Detection in a non destructive manner while keeping the evidence as it is, is an important field in forensic sciences. Hyperspecteral Images can be used to Identify Blood. For that The Authors of [1] used several techniques and the 3D CNN performed best and showed great success. In this notebook, We've implemented the architecture they proposed for 3D CNN and presented the results. We have done 
- Tiling of data
- Principal Component Analysis for Dimension Reduction
- SMOTE for balancing the data
- Normalization of Data
- Model Training
- Model Prediction
- Classification Report

The Dataset can be found [here](https://zenodo.org/record/3984905#.ZBbn1HZBzIU) 

![image](https://github.com/GoSleepBelall/Blood-Stain-Detection-using-3D-CNN/assets/86932331/6be10ca6-364e-43e7-9c3a-472a3c8bdda6)

- Tiling for 9x9 was done on every image:


![image](https://github.com/GoSleepBelall/Blood-Stain-Detection-using-3D-CNN/assets/86932331/5560b75a-6f70-401f-9710-df6a1fe6c96d)

after which the model was able to classify each tile properly and successfully achieved 99% accuracy.

![image](https://github.com/GoSleepBelall/Blood-Stain-Detection-using-3D-CNN/assets/86932331/a5be3dbe-bd4d-4161-9b31-01c51e953671)
