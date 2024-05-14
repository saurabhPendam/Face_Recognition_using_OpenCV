# Face_Recognition_using_OpenCV
Face recognition is a method of identifying or verifying the identity of an individual using their face. Face recognition systems can be used to identify people in photos, video, or in real-time. 


Fisherface Recognizer:
-Fisherfaces algorithm extracts principle components that separates one individual from another. So , now an individual's features can't dominate another person's features.

- Fisherface method will be applied to generate feature vector of facial image data used by system and then to match vector of traits of training image with vector characteristic of test image using euclidean distance formula

![image](https://github.com/saurabhPendam/Face_Recognition_using_OpenCV/assets/86524882/df8b8c66-3390-4c0e-a8de-c8101841cec3)


LBPHFaceRecognizer:
Local Binary Pattern (LBP) is a simple yet very efficient texture operator which labels the pixels of an image by thresholding the neighborhood of each pixel and considers the result as a binary number.

It doesn't look at image as a whole, but instead tries to find its local structure by comparing each pixel to its neighboring pixels.

LBPH uses 4 parameters
- Radius - to build the circular local binary pattern and represents the radius around the central pixel. It is usually set to 1.
- Neighbors - : The more sample points you include, the higher the computational cost. It is usually set to 8
- X Grid - the number of cells in the horizontal direction.
- Y Grid - the number of cells in the vertical direction.

![image](https://github.com/saurabhPendam/Face_Recognition_using_OpenCV/assets/86524882/3f0b8c56-8a48-4025-9d29-d1bba343fc88)

![image](https://github.com/saurabhPendam/Face_Recognition_using_OpenCV/assets/86524882/30010c6f-62df-45f1-b2e6-5a0dfd0de259)
