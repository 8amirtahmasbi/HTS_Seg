# HTS-Seg: Heterotypic Tumor Spheroids Segmentation Dataset  

## Description  
The **HTS-Seg** dataset is available on Zenodo at [this link](https://doi.org/10.5281/zenodo.11542859). It contains microscopy images of heterotypic tumor spheroids along with their segmentation masks. The dataset is composed of:  

- **97 full-sized microscopy images** with dimensions of **2160 × 3840 pixels**, divided into two classes:  
  - **49 images from the control class**  
  - **48 images from the treatment class**  

- **2,980 cropped and resized images** at **512 × 512 pixels**, categorized as follows:  
  - **1,515 images from the treatment class**  
  - **1,465 images from the control class**  

- **2,180 cleaned tiled images** at **512 × 512 pixels**, classified as:  
  - **1,089 images from the treatment class**  
  - **1,091 images from the control class**  

- Two CSV files containing relevant metadata:  
  - `ImageFeatureDataset.csv`  
  - `spheroid_time_series.csv`  

This dataset can be used for training and evaluating image segmentation models, particularly for the task of heterotypic tumor spheroid segmentation. The full-sized images can be used for model development, while the cropped and resized images facilitate faster training and testing.  

## Dataset Contents  
- **Full-sized Microscopy Images:**  
  - **Total:** 97 images (2160 × 3840 pixels)  
    - **Control Class:** 49 images  
    - **Treatment Class:** 48 images  

- **Cropped and Resized Images:**  
  - **Total:** 2,980 images (512 × 512 pixels)  
    - **Treatment Class:** 1,515 images  
    - **Control Class:** 1,465 images  

- **Cleaned Tiled Images:**  
  - **Total:** 2,180 images (512 × 512 pixels)  
    - **Treatment Class:** 1,089 images  
    - **Control Class:** 1,091 images  

- **Metadata Files:**  
  - `ImageFeatureDataset.csv`  
  - `spheroid_time_series.csv`  

## Usage  
This dataset can be utilized for training and evaluating image segmentation models, particularly for the task of heterotypic tumor spheroid segmentation. The full-sized images can be used for model development, while the cropped and resized images can be used for faster training and testing.  

## Contact  
For any questions or feedback about the dataset, please contact the dataset creator:  
- Amir Tahmasbi (8amirtahmasbi@gmail.com)
