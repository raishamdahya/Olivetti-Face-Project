# Olivetti-Face-Project
The purpose of this project is to develop a face recognition model using the Olivetti faces dataset. 

Initially, a basic face recognition model was built using a KNN Classifier to find the best mathcing image in the training data of each of the facial images in the test data. This KNN model achieved an accuracy of 87.5%. To increase the accuracy of this model a PCA transformer was applied, however it did not increase the accuracy and it remained at 87.5%. A model was then built using a C-Support Vector Machine Classifier with a RBF kernel alongside a GridSearch CV. This facial recognition model acheived 92.5% accuracy. This accuracy significantly improved from using a KNN classifier.

