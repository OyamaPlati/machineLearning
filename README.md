# Automatic Detection of Drones in NeXtRAD data using Machine Learning

# Transfer Learning
We explored transfer learning in conjunction with Google's Inception-V3 architecture. 
We employ some techniques to deal with the lack of data. Upon training the top layers of the pre-trained Inception-V3 architecture 
to fit our model we then used two more layers to perform binary classification for drone and nodrone detection.

# Ensemble Learning
We used different dimensionality reduction and feature extraction methods such PCA, linear KPCA, polynomial KPCA and RBF KPCA for on the nextrad data. 
Split the training data by 10% to 90% during training and evaluation while keeping the testing set constant. 
We then use ensemble learning to create a powerful binary classifier for training, validation and testing.
