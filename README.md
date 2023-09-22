# Facemask-Detection-Using-CNN

Dataset : https://github.com/balajisrinivas/Face-Mask-Detection/tree/master/dataset

## Abstract
The world started to show concerns about the benefits of AI than its apocalypse. People have started to solve complex problems using AI, So do we. I took the problem of detecting and classifying whether a person wearing a face mask or not. As this pandemic became new normal it is important to wear a face mask and make sure whether people around us wear a face mask. Let us allow AI to take care of that. Using a two-step pipeline to solve this problem.
From the video capture, I fetched a single frame using OpenCV, And I passed the fetched frame to the Viola-Jones face detector(HaarCascade face detector). After the detector detects the faces, I cropped the face ROI(Region of Interest) and passed it into popular CNN architecture named VGG16 to classify whether the face ROI contains a face mask or not.
