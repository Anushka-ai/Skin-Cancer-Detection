# Skin-Cancer-Detection
Trained a CNN model, to detect the skin cancer using image dataset.
Mole Classifier Kernel
Skin cancer is the most common human malignancy, is primarily diagnosed visually, beginning with an initial clinical screening and followed potentially by dermoscopic analysis, a biopsy and histopathological examination. Automated classification of skin lesions using images is a challenging task owing to the fine-grained variability in the appearance of skin lesions.

The dataset is taken from the ISIC (International Skin Image Collaboration) Archive. It consists of 1800 pictures of benign moles and 1497 pictures of malignant classified moles. The pictures have all been resized to low resolution (224x224x3) RGB. The task of this kernel is to create a model, which can classify a mole visually into benign and malignant.

As the dataset is pretty balanced, the model will be tested on the accuracy score, thus (TP + TN)/(ALL).

It has 2 different classes of skin cancer which are listed below :
1. Benign
2. Malignant

In this kernel I will try to detect 2 different classes of moles using Convolution Neural Network with keras tensorflow in backend and then analyse the result to see how the model can be useful in practical scenario.

In this kernel I have followed following 14 steps for model building and evaluation which are as follows :
Step 1 : Importing Essential Libraries
Step 2: Loading pictures and making Dictionary of images and labels
Step 3: Categorical Labels
Step 4: Normalization
Step 5: Train and Test Split
Step 6: Model Building **
**Step 7: Cross-validating model
Step 8: Testing model
Step 9: ResNet50
