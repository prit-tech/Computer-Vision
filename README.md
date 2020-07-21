
Data Description: Aligned Face Dataset from Pinterest. This dataset contains 10.770 images for 100 people. All images are taken from 'Pinterest' and aligned using dlib library.

Objective: In this problem, we use a pre-trained model trained on Face recognition to recognize similar faces. Here, we are particularly interested in recognizing whether two given faces are of the same person or not.

Steps and Tasks:

Load the dataset and create the metadata.
Check some samples of metadata.
Load the pre-trained model and weights.
Generate Embedding vectors for each face in the dataset.
Build distance metrics for identifying the distance between two given images.
Use PCA for dimensionality reduction.
Build SVM classifier to map each image to its right person.
Predict using the SVM model.
Face recognition
Task is to recognize a faces
