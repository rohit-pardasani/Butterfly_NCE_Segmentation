# Butterfly_NCE_Segmentation
The intent of this project is to train encoder using noise contrastive estimation on a large dataset. 
Then use this pre trained encoder in a segmentation model. 
Train only the decoder of the model with a small segmented dataset.

# Dataset
https://www.kaggle.com/datasets/phucthaiv02/butterfly-image-classification

The above mentioned dataset has two folders:
Train: 6499
Test: 2786

For training unsupervised NCE all 6499 images from train set have been used.

For Segmentation, contours were created as in .csv files.

Training Set: 100 images from the original Train set of 6499 were used. Contours are available in .csv file. Names of files were retained.
Validation Set: 20 images from the original Train set of 6499 were used. Contours are available in .csv file. Names of files were retained.
Test Set: 30 images from the original Test set of 2786 were used. Contours are availabel in .csv file. Names of files were retained.

