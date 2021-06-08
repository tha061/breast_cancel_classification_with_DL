# breast_cancel_classification_with_DL
The goal of this project is to build a breast cancer classifier on an IDC dataset that can accurately classify a histology image as benign or malignant.

# Method


# Data set: IDC_regular dataset from Kaggle
This dataset holds 2,77,524 patches of size 50×50 extracted from 162 whole mount slide images of breast cancer specimens scanned at 40x. Of these, 1,98,738 test negative and 78,786 test positive with IDC. 

Link to download the dataset: https://www.kaggle.com/paultimothymooney/breast-histopathology-images/

Filenames in this dataset look like this: 8863_idx5_x451_y1451_class0
Here, 8863_idx5 is the patient ID, 451 and 1451 are the x- and y- coordinates of the crop, and 0 is the class label (0 denotes absence of IDC).

# Requirements
pip install numpy opencv-python pillow tensorflow keras imutils scikit-learn matplotlib
