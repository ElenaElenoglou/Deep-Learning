## Lungs Deseases Classificiation

#### Problem Statement: 
Implement an algorithm to classify whether pneumonia is detected in lungs X-ray images.

#### Dataset:
The total number of images available for training the model is 5216 and for testing the model is 624 images.
• Dataset Link: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia?

### Dependencies:
* Keras
* Tensorflow - 2.2.0
* Python - 3.6
* Pandas
* Numpy
* Matplotlib
* Glob

### Data Augmentation:
* Shearing of images
* Random zoom
* Horizontal flips

![DataAugmentation](https://user-images.githubusercontent.com/60225335/89791474-ab26b380-db23-11ea-8287-aef05ce02a13.PNG)

### Network Parameter:
* Rectifier Linear Unit (ReLU) - Hidden Layers
* Softmax - Output Layer
* Adam optimizer
* Loss: Categorical Crossentropy

![NetworkParameter](https://user-images.githubusercontent.com/60225335/89800550-3d808480-db2f-11ea-9773-ab03c12aa341.PNG)

### Visualization of Model Accuracy:
* Training Set Accuracy: 94.75% 
* Validation Accuracy: 90.87%

![Accuracy](https://user-images.githubusercontent.com/60225335/89801476-838a1800-db30-11ea-92f6-0f0d7b448658.png)

### Visualization of Model Loss:
* Training Set Loss: 0.1333
* Validation Loss: 0.3425

![Loss](https://user-images.githubusercontent.com/60225335/89801772-e7144580-db30-11ea-96ca-ce64e5e20330.png)


