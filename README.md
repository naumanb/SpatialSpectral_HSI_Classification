# Hyperspectral Image Classification Using Fusion of Spectral and Spatial Features
## Project Description
This project explores the classification of hyperspectral images using a fusion of spectral and spatial features. Hyperspectral imaging (HSI) is a computer vision modality that combines standard 2D imaging with spectroscopy to acquire a three-dimensional hypercube. HSI has been used in various fields, such as remote sensing and medical image diagnosis. The goal of this project is to improve the accuracy and efficiency of hyperspectral image classification by incorporating spatial features along with spectral features.

The project implements and compares two spatial-spectral HSI classification methods and evaluates their performance in terms of accuracy, kappa coefficient, and total time taken.

## Implemented Methods
- Semi-supervised learning method for classification based on Spatial Majority Voting [5].
- Edge-Preserving Filters (EPFs) method with PCA-based dimensionality reduction [6].

## Installation
1. Install MATLAB (version R2021a or later) from the official website.
2. Clone this repository to your local machine.
3. Install necessary MATLAB toolboxes:
- Image Processing Toolbox
- Statistics and Machine Learning Toolbox

## Usage
1. Download the following datasets:
- AVIRIS Indian Pines dataset: [Indian Pines Dataset](https://purr.purdue.edu/publications/1947/1)
- Pavia University dataset: [Pavia University Dataset](http://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes#Pavia_University_scene)
- Pavia Centre dataset: [Pavia Centre Dataset](http://www.ehu.eus/ccwintco/index.php?title=Hyperspectral_Remote_Sensing_Scenes#Pavia_University_scene)

2. Place the downloaded datasets in the `data` folder within the `SpatialMajorityVoting` and `PCA-EPFs` directories.

### For Spectral Classifier
1. Open the `SpatialMajorityVoting` folder in MATLAB.
2. Run the `DemoSpectralClassifier` MAT file.

### For SpatialMajorityVoting Classifier
1. Open the `SpatialMajorityVoting` folder in MATLAB.
2. Run the `DemoSpatialClassifier.m` MAT file.

### For PCA-EPFs Classifier
1. Open the `PCA-EPFs` folder in MATLAB.
2. Run the `pca_epfssdemo.m` MAT file.

## Dataset
The dataset used in this project is the AVIRIS Indian Pines dataset, which consists of an HSI image of 145x145 pixels and 224 different spectral bands. The scene includes agricultural, forest, and vegetation objects, as well as structures such as highways, rail lines, and housing. Objects within the scene are distributed into 16 different class labels of crops, such as corn and soybeans.

## Results
The performance of the implemented classification methods is evaluated using the overall accuracy, kappa coefficient metrics, and total time taken. 

![metric_results](https://user-images.githubusercontent.com/15255699/234968531-943a91df-767a-4b2d-b878-b29460c6b236.png)



## License
This project is released under the MIT License. See LICENSE for details.

## Acknowledgements
This project was developed by Nauman Baig under the supervision of Prof. Ling Guan at Ryerson University.

## References
[1] Kang Xudong (2020). Hyperspectral Image Classification (https://www.mathworks.com/matlabcentral/fileexchange/69242-hyperspectral-image-classification), MATLAB Central File Exchange. Retrieved April 18, 2020.

[2] Galad_Loth (2020). Hyperspectral Image Classification (https://github.com/galad-loth), Github.
