# HTS_Seg
HTS-Seg: Heterotypic Tumor Spheroids Segmentation Dataset
Description
The HTS-Seg dataset contains microscopy images of heterotypic tumor spheroids along with their segmentation masks. The dataset consists of 97 full-sized images with dimensions 2160 × 3840 pixels, divided into two classes: control (49 images) and treatment (48 images). Additionally, there are 2,980 tiled images at 512 × 512 pixels, with 1,515 belonging to the treatment class and the rest to the control class. The dataset also includes a “ImageFeatureDataset.csv”  file containing relevant information about the images.
Dataset Contents
•	97 full-sized microscopy images (2160 × 3840 pixels) 
o	48 treatment class images
o	49 control class images
•	2,980 cropped and resized images (512 × 512 pixels) 
o	1,515 treatment class images
o	1,465 control class images
•	1 CSV file with metadata about the images
Usage
This dataset can be used for training and evaluating image segmentation models, particularly for the task of heterotypic tumor spheroid segmentation. The full-sized images can be used for model development, while the cropped and resized images can be used for faster training and testing.
Contact
If you have any questions or feedback about the dataset, please contact the dataset creator:
•	Amir Tahmasbi (8amirtahmasbi@gmail.com)
