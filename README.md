# Disgnosis of Skin Cancer Using Transfer Learning Approach

<pre>
Domain             : Computer Vision, Machine Learning
Sub-Domain         : Deep Learning, Image Recognition
Techniques         : Deep Convolutional Neural Network, XceptionNet
Application        : Image Recognition, Image Classification, Medical Imaging
</pre>

### Project Highlights
<pre>
1. Detected 3 types of skin cancer from Skin Lesion images using Transfer Learning MobileNetV2 architecture with 12,295 Skin Lesion images 
(Basal Cell Carcinoma : 3273 images, Nevus (Benign) : 4550 images, Melanoma : 4472 images).
2. For classifying Basal Cell Carcinoma, Nevus and Melanoma classes architecture of pretrained network MobileNetV2 used.
3. Customized MobileNetV2 Network attained testing accuracy of 96.94%.
</pre>

#### Dataset
<pre>
Dataset : <a href=https://challenge.isic-archive.com/data/>ISIC Skin Cancer Challenge 2019</a>

                   
</pre>
The sample images of Basal cell Carcinoma, Melanoma and Nevus are shown in figure below:

![Sample Image of Skin Lesion](https://i.ibb.co/MfmmrfJ/thumbnail.png)

<pre>
<b>Dataset Details</b>
Dataset Name            : ISIC Skin Cancer Images (Basal Cell Carcinoma vs Melanoma vs Nevus)
Number of Class         : 3
Number/Size of Images   : Total      : 12445 (555 MB)
                          Training   : 12295
                          Testing    : 150 
                         
</pre>
#### Results
We have achieved following results which outperform 4 previous state-of-the-art deep CNNs for detection of Skin Cancers.

<pre>
<b> Performance Metrics </b>
Test Accuracy                                    : 97.47%
Precision                                        : 97%
Sensitivity (BCC)                                : 100% 
Sensitivity (Melanoma)                           : 96% 
Sensitivity (Nevus)                              : 98%
F1-score                                         : 98%
AUC                                              : 0.99
</pre>

#### ROC AUC Curve

![ROC AUC Curve](https://i.ibb.co/1v30GvF/roc.png)
