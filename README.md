# Breast-Cancer-Detection

### Problem statement : 
Breast cancer is the most prevalent form of cancer among women, with Invasive Ductal Carcinoma (IDC) being its most common subtype. While mammograms and ultrasounds can detect tumors, histopathology images provide crucial information about malignancy at the cellular level. Developing a Computer-Aided Diagnostic (CAD) system is essential to offer objective and consistent interpretations, aiding medical professionals in early breast cancer detection, prognosis, treatment planning, and ultimately improving patient outcomes while reducing screening costs.Our main onjective is to identify breast cancer (IDC) in breast histopathology images using Convolutional Neural Networks (CNNs).

### Project Description :
This project employs Convolutional Neural Networks (CNNs) to detect Invasive Ductal Carcinoma (IDC) in breast histopathology images, aiding early breast cancer diagnosis. With 277,000 images, we address class imbalance through oversampling and weights and data augmentation. We explore multiple CNN models, regularization techniques, and transfer learning, optimizing model performance with Adam optimization and binary cross-entropy loss. We evaluate model performance using F1 score, precision, recall, precision recall curve and accuracy to ensure robustness and accuracy. Also, utilized cosine learning rate decay to gradually decrease the learning rate, aiding faster convergence to the global minimum and preventing oscillations.

### Data source:
Dataset is available on Kaggle at the following link : https://www.kaggle.com/datasets/paultimothymooney/breast-histopathologyimages

### What analysis were performed : 
```Breast_Cancer_Detection.ipynb``` : Code four models  :<br>
Baseline(Naive) Mode : Randomly assigned class label based on class probability distribution in training data<br>
Model 1 : CNN with Regularization <br>
Model 2 : CNN with Residual Network <br>
Model 3 : CNN with Transfer Learning

<img width="1015" alt="image" src="https://github.com/aasthatandon/Breast-Cancer-Detection/assets/28407844/61784292-81df-4df2-b010-6a1662d6629e">


<img width="1018" alt="image" src="https://github.com/aasthatandon/Breast-Cancer-Detection/assets/28407844/62eee107-4b5e-42f2-9b6a-d75e1abc7b43">


<img width="1017" alt="image" src="https://github.com/aasthatandon/Breast-Cancer-Detection/assets/28407844/03c377ca-3b61-463c-81bb-5f3c5915f33c">


### Files Overview:
```Breast_Cancer_Detection.ipynb```: Analysis Codes <br>
```Breast_Cancer_Detection_presentation``` : Project Presentation   
