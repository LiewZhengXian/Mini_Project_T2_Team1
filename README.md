# Mega Project
## Overview
This repository contains the code and files for the T2 Team1 Traffic Sign Detection project under the UCCC2513 course. The project is focused on experimenting 2 types of denoising methods, which are Gaussian blur and Median blur, and 3 types of edge detection methods, which are Canny Edge Detection, Gabor Filter, and Structured Forest Model for Traffic Sign Detection. At the end, we compares based on the performance and execution time on each pipeline with different denoising method and edge detection method and finally we deduced the best pipeline which is using the Gaussian blur + Structured Forest Model.
## Installation
### Dataset
In this project, we used 4170 data from Chinese Traffic Sign Database.
Download Link: https://nlpr.ia.ac.cn/PAL/TRAFFICDATA/recognition.html
Note: Please download the **TSRD-test** under the download section
### Structured Forest Model
In this project, the trained model for Structured Forest is downloaded for edge detection.
Download Link: https://github.com/opencv/opencv_extra/blob/5e3a56880fb115e757855f8e01e744c154791144/testdata/cv/ximgproc/model.yml.gz
#### How to use?
##### <u>Setup</u>
Download and run the **ipynb** files with installed dataset and trained model for Structured Forest in the correct directories name (full_images for 4170 dataset, model.yml for trained model).
##### <u>Dataset Testing</u>
In main function for each edge detection method, you can choose to test 4170 images with path name **full_images** or 101 chosen images with path name **images** by commenting/uncommenting the **img_dir** variable.
##### <u>Interface using Gradio</u>
Install the **Gradio** library before you use the interface located at the last section in the file.

