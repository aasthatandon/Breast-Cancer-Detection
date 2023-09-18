# Breast-Cancer-Detection

### Problem statement : 
Breast cancer is the most prevalent form of cancer among women, with Invasive Ductal Carcinoma (IDC) being its most common subtype. While mammograms and ultrasounds can detect tumors, histopathology images provide crucial information about malignancy at the cellular level. Developing a Computer-Aided Diagnostic (CAD) system is essential to offer objective and consistent interpretations, aiding medical professionals in early breast cancer detection, prognosis, treatment planning, and ultimately improving patient outcomes while reducing screening costs.Our main onjective is to identify breast cancer (IDC) in breast histopathology images using Convolutional Neural Networks (CNNs).

### Project Description :
This project employs Convolutional Neural Networks (CNNs) to detect Invasive Ductal Carcinoma (IDC) in breast histopathology images, aiding early breast cancer diagnosis. With 277,000 images, we address class imbalance through oversampling and weights and data augmentation. We explore multiple CNN models, regularization techniques, and transfer learning, optimizing model performance with Adam optimization and binary cross-entropy loss. Also, utilized cosine learning rate decay to gradually decrease the learning rate, aiding faster convergence to the global minimum and preventing oscillations.

### Data source:
Dataset is available on Kaggle at the following link : https://www.kaggle.com/datasets/paultimothymooney/breast-histopathologyimages

### What analysis were performed
```Breast_Cancer_Detection.ipynb``` : Code for the three models  :<br>
Model 1 : CNN with Regularization <br>
Model 2 : CNN with Residual Network <br>
Model 3 : CNN with Transfer Learning

```Breast_Cancer_Detection_presentation``` : Project Presentation   
