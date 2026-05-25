# FACE_MASK-DETECTION-SYSTEM-USING-BINARY-CLASSIFICATION
Face mask detection system using binary classification helps to detect person who is with and without mask

SIMPLE PROJECT FLOW : OpenCV + TensorFlow/Keras(mobileNetV2)
# INSATALL REQUIRED PACKAGES 
PACKAGES I USED IN THE PROJECT:   1  -->  Opencomputervision
                                  2  -->  tensorflow
																	3  -->  numpy
																	4  -->  matplotlib
																	5  -->  scikit-learn
# CREATE TWO IMAGE DIRECTORIES 
* Image Folder
*     --->with mask
*     --->without mask  
* Used to store captured images from computervision with and without mask images
* While the the CV starts capturing withmask images (first you should wear a mask)
* Then without mask images
* PRESS Q TO STOP CATURING

# Load images and pre-process for Mobilenetv2
* Here shows the tensor flow version and total loaded images with and without mask
* with mask:75
* without mask:75
* Total images loaded : some number it shows(ex:150)
# HERE THE IT TRAIN AND TEST SPLIT 
* The model get trained with help of total stored images
* Two things here happened
  --->train
  --->test split

# MODEL READY  
* Train the model with saved model---> mask_detector .h5
* Best model ---> mask_detector_best.h5

# VISUALISE TRAINING CURVES (matplotlib)
*  How much Accuracy the images are captured it shows the visualise training results
*  Loss of the image clarity also it shows by the visualization
  
