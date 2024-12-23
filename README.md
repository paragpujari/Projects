 # Brain Tumor Classification and Detection - Deep Learning Approach

 ## Overview

 Cancer is one of the most deadliest disease that we face today. Detecting tumors early can serve as a potential indicators of cancer which is crucial in our fight against  this formidable adversary. As AI tools continue to evolve and find applications in medicine and image diagnostics, they become valuable allies in tumor detection alongside healthcare professionals.However, it’s essential to emphasize that AI should not replace professional diagnosis. Instead, it serves as a supportive tool, assisting clinicians in their assessments.


 In this project, we are using the deep learning model named CNN(Convolutional Neural Networks) for detecting whether the brain images provided to us has tumor in it or not.

## Dataset

The brain tumor dataset has two sets of folder 'No' and 'Yes'.

(i) No folder = It contains the list of all the brain images that are not detected with brain tumor. There are total 98 images that are not detected with brain tumor.

(ii) Yes folder = It contains the list of all the brain images that are detected with brain tumor.   There are total 155 images that are detected with brain tumor.


## Approach

# (i) Creating 3 Important Lists for storing the data.
     a. data  - It contains all the data in the numpy array form.
     
     b. paths - It contains the paths where the images are to be stored. 

     c. result - It contains the result of whether the brain image has a tumor or not.

# (ii) Splitting the dataset into training and testing data.
    a. Here the dataset is split into training and testing data i.e training data has 80 % data and testing has 20 % data.

# (iii) Model Building
    a.  Here we are using a Convolutional Neural Network (CNN) to build the neural network. In this process, Batch Normalization is used where the input network is converted into layers for each and every epoch. It helps in stabilizing the learning process and reduces the number of epochs for every learning process.

# The hyperparameters used in this project is of below:

 .   Input: 128 * 128 * 3

 .   Num epochs: 30

 .   Batch size: 40

 .   verbose : 1


# Project Results

The model used on MRI images test set provides the following result:

Accuracy for Non Tumor Dataset :    (100% Accuracy)

Accuracy for Tumor     Dataset :    (61.17897629737854% Accuracy)

