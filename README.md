# 2023-Publication_Yolo-Detection-3D-Pose-Tracking-
In this section we introduce a Yolo Detection algorithm for 3D Pose Tracking of Cardiac Catheters.
With the increasing rate of minimally invasive surgeries and the growing prevalence of cardiovascular diseases have led to a demand for higher quality guidance systems for catheter tracking. 
Traditional methods for catheter tracking, such as one-point detection and masking, have been limited in their ability to provide accurate pose information. 
In this work, we propose a novel deep learning-based method for catheter tracking and pose detection. 
Our method uses a Yolov5 bounding box neural network with post-processing to perform landmark detection in four regions of the catheter: the tip, radio-opaque marker, bend, and entry point. 
This allows us to track the catheter's position and orientation in real time, without the need for additional masking or segmentation techniques. 
We evaluated our method on a dataset of fluoroscopic images from two distinct datasets and achieved state-of-the-art results in terms of accuracy and robustness. 
Our method was able to accurately detect the entry point, catheter tip and radio-opaque marker, even in challenging conditions. 
Our results indicate a 3D euclidean distance of 0.235 ± 0.085 (mm) between prediction and ground truth for the entry followed by 0.261 ± 0.138 (mm), 0.285 ± 0.143 (mm) and 0.424 ± 0.361 (mm) for marker, tip, and bend respectively. 
We believe that our method has the potential to significantly improve the accuracy and efficiency of catheter tracking in real-world applications. 


For using the code provided in this repository we have provided access to two datasets, one containing 1429 samples, a combinatory dataset and the other a 900 paired dataset. 
The second dataset has been generated for 3D coordinate detection and contains the images to two planes: AP and LAO90, setting a 90 degree angle with each other.