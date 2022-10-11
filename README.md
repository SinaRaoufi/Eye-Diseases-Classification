# Eye diseases classification 👁️
Eye Diseases Classification with CNN using pytorch


## Dataset:
The dataset consists of Normal, Diabetic Retinopathy, Cataract, and Glaucoma retinal images, where each class has approximately 1000 images. These images are collected from various sources like IDRiD, Oculur recognition, HRF, etc.

The dataset can be downloaded here: https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification

### Examples:

Cataract  

<img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/cataract.jpg" width="128" height="128" />

Diabetic Retinopathy

<img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/diabetic_retinopathy.jpeg" width="128" height="128" />

Glaucoma

<img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/glaucoma.jpg" width="128" height="128" />

Normal

<img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/normal.jpg" width="128" height="128" />



## Model:
For this classification, I use a Convolutional neural network (CNN) which is made of convolution stages (Conv2d, ReLU, MaxPool2d) and a fully connected layer at the end.
