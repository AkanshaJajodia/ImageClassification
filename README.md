# ImageClassification

Dataset Information
The dataset contains images of 11 classes. Provided datasets are features extracted from images where the training and test data are in dense matrix, and 
training labels are provided as integers. The training dataset in composed of images described as 887-dimensional vectors highly unbalanced and has 
887-dimensional vectors composed by concatenating the following features:

   - 512 Histogram of Oriented Gradients (HOG) features 
   - 256 Normalized Color Histogram (Hist) features
   - 64 Local Binary Pattern (LBP) features 
   - 48 Color gradient (RGB) features 
   - 7 Depth of Field (DF) features 
The training dataset contain 18000 records and the test data consists of 3000 records as described below:

   - train.dat: Training set (dense matrix, samples/images in lines, features in columns). 
   - train.labels: Training class labels (integers, one per line). 
   - test.dat: Test set (dense matrix, samples/images in lines, features in columns). 
   - format.dat: A sample submission with 3000 entries randomly chosen to be 1-11. 
