# Optical-Music-Recognition
This is an Optical Music Recognition model following a Deep Learning Approach for note and symbol recognition.

- The model building file shows a comparison of 4 CNN models, VGG16, VGG19, ResNet101 and MobileNetV2 running on pre-trained weights. 
- The omrdatasettools library is used to download the Rebelo dataset for recognition and classification
- Based on the Validation loss and the accuracies recorded, the VGG16 model was chosen as the best performed model.

The "Image to Note" python file shows the OMR model running Binarization, Staff Line Removal, and symbol recognition. 
The VGG16 model is used for classification and recognition in this model.
