# Butterfly_NCE_Segmentation
The intent of this project is to train encoder using noise contrastive estimation on a large dataset. 
Then use this pre trained encoder in a segmentation model. 
Train only the decoder of the model with a small segmented dataset.

## Dataset
https://www.kaggle.com/datasets/phucthaiv02/butterfly-image-classification

The above mentioned dataset has two folders:
Train: 6499
Test: 2786

For training unsupervised NCE all 6499 images from train set have been used.

Trained Model Link: https://drive.google.com/file/d/1qPIVWF4neh3B5-OxJOJxozKzVfwVP9RF/view?usp=drive_link


## For Segmentation, contours were created as in .csv files. The images, contours and masks can be found in Segmented Dataset

**Training Set:** 100 images from the original Train set of 6499 were used. Contours are available in .csv file. Original names of files were retained.

**Validation Set:** 20 images from the original Train set of 6499 were used. Contours are available in .csv file. Original names of files were retained.

**Test Set:** 30 images from the original Test set of 2786 were used. Contours are availabel in .csv file. Original names of files were retained.

