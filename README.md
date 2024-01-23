### About the dataset and data


- Imbalanced dataset referred of oil spill.
- Dataset was introduced in the 1998 paper by Miroslav Kubat, et al. titled Machine Learning for the Detection of Oil Spills in Satellite Radar Images
- The dataset consisted of satellite images of the ocean, some of which contain an oil spill and some that do not. Images were split into sections and processed using computer vision algorithms to provide a vector of features to describe the contents of the image section or patch.
- In my project, model is given a vector that describes the contents of a patch of a satellite image, then predicts whether the patch contains an oil spill or not.
- Binary data, no oil spill assigned the class label of 0, whereas an oil spill is indicated by a class label of 1. There are 896 cases for no oil spill and 41 cases of an oil spill.
