# Diabetic-Retinopathy-Classifier-Using-ResNet18
A simple Diabetic Retinopathy classifier using a fine tuned ResNet model trained on a 3000 labled fundus images
Diabetic retinopathy is the leading cause of blindness in the working-age population of the developed world. It is estimated to affect over 93 million people.

![alt text](https://camo.githubusercontent.com/1be5f063609d021dade5bd8c775e8e7162f242d10e43e0f8bdc614c9aaa1cc73/68747470733a2f2f73746f726167652e676f6f676c65617069732e636f6d2f6b6167676c652d636f6d7065746974696f6e732f6b6167676c652f343130342f6d656469612f726574696e612e6a7067)

The US Center for Disease Control and Prevention estimates that 29.1 million people in the US have diabetes and the World Health Organization estimates that 347 million people have the disease worldwide. Diabetic Retinopathy (DR) is an eye disease associated with long-standing diabetes. Around 40% to 45% of Americans with diabetes have some stage of the disease. Progression to vision impairment can be slowed or averted if DR is detected in time, however this can be difficult as the disease often shows few symptoms until it is too late to provide effective treatment.

Currently, detecting DR is a time-consuming and manual process that requires a trained clinician to examine and evaluate digital color fundus photographs of the retina. By the time human readers submit their reviews, often a day or two later, the delayed results lead to lost follow up, miscommunication, and delayed treatment.

As such, the classification of such disease was proposed multiple times in form of competitions in kaggle, and this model aims to tackle this one :
https://www.kaggle.com/competitions/diabetic-retinopathy-detection

You can download the dataset in the link mentioned above, the dataset is labeled for the 5 classes of DR : 

**0 - No_DR**

**1 - Mild**

**2 - Moderate**

**3 - Severe**

**4 - Proliferate_DR**

But this model aims to only provide a binary classifaction, as such, its able to classify the dataset to : 
**0 - No_DR**

**1 - DR**

A ResNet18 Model was used and Fine-Tuned by freezing some of the layers while keeping the classifying layers (Fully connected layers) and a 98% acc was achieved for the validation test, on a 500 images set with 2000 images set attributed to the training phase,the dataset's is from the APTOS 2019 Blindness Detection.

<font size= “8”> A graph showing the ResNet Architecture :</font>
![alt text](https://raw.githubusercontent.com/MaladAhmed/Diabetic-Retinopathy-Classifier-Using-ResNet512/main/images%20for%20the%20preview/Original-ResNet-18-Architecture.png)


![alt text](https://raw.githubusercontent.com/MaladAhmed/Diabetic-Retinopathy-Classifier-Using-ResNet512/main/images%20for%20the%20preview/download.png)











