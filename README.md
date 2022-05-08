# Image Processing
Image Processing with OpenCV.<br>
## Introduction
This project includes the following implementations:<br>
1. Feature Extraction with HSV color space.
2. Morphology: i.Erosion, ii.Dilation, iii.Opening, iv.Closing.
3. Canny Edge Detection.
4. Thresholding (Binarization).

## Original Image
![](https://github.com/TW-ZJLin/ImageProcessing/blob/main/Figures/Original.jpg)<br>

## Demonstration
### Feature Extraction with HSV color space
Convert image to HSV color space.<br>
Extract blue and black features and combine them.<br>
![](https://github.com/TW-ZJLin/ImageProcessing/blob/main/Figures/FeatureExtraction.jpg)<br>

### Morphology:
Three kind of kernels as shown below.<br>
![](https://github.com/TW-ZJLin/ImageProcessing/blob/main/Figures/MorphologyKernel.jpg)<br>

Four common types of Morphological Operations<br>
i. Erosion, ii. Dilation, iii. Opening, iv. Closing.<br>
![](https://github.com/TW-ZJLin/ImageProcessing/blob/main/Figures/Morphology.jpg)<br>

Fill the hole with the closing operation that iterates 16 times.<br>
![](https://github.com/TW-ZJLin/ImageProcessing/blob/main/Figures/HoleFilling.jpg)<br>

### Canny Edge Detection:
Blur grayscale images with Gaussian blur.<br>
Use canny to detect image edge.<br>
![](https://github.com/TW-ZJLin/ImageProcessing/blob/main/Figures/CannyEdgeDetection.jpg)<br>

### Thresholding (Binarization):
Compare three binarization methods: 1.Normal Thresholding, 2.Adaptive Mean Thresholding, 3.Adaptive Gaussian Thresholding.<br>
And compare the effect of blurring on image binarization.<br>
![](https://github.com/TW-ZJLin/ImageProcessing/blob/main/Figures/Thresholding.jpg)<br>
