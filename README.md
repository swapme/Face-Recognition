# Face-Recognition
Face recognition has been one of the most popular research area in field of computer vision. In face/object recognition we can use sparseness of image for classifying object. We must be able to properly use the sparsity. We use sparse representation for set of images to correctly classify the test image by solving system of linear equations. 
In this project I have implemented various feature extraction techniques and classifying them with  different algorithms. Main focus is to prove how sparse representation perform better than other classifiers such as svm, nearest neighbour and nearest subspace. I tried Eigenface,  Randomfaces and downsampling as feature extraction techniques. The main problem we face is computation as face image can be very high dimensional. We use l1minimization to solve constructed linear equations.
We will show how sparse representation classifier can be helpful in classifying occluded or corrupted images. Non zero values in sparse solution will correspond to same persons images in training set. 



