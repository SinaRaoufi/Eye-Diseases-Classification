# Eye Diseases Classification 👁️
The early detection of eye diseases is essential for preserving vision and preventing further damage. Many eye diseases, such as diabetic retinopathy and glaucoma can have few or no symptoms in their early stages. By the time symptoms appear, the disease may have progressed to a point where it is much harder to treat. Early detection also provides an opportunity to start appropriate treatment that can help manage the condition and prevent vision loss. Consequently, early detection of these diseases is so crucial because people can lose their vision.

## Dataset
The dataset consists of Normal, Diabetic Retinopathy, Cataract, and Glaucoma retinal images, where each class has approximately 1000 images. These images are collected from various sources like IDRiD, Oculur recognition, HRF, etc.
The dataset can be downloaded here: https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification

### Examples:

**Cataracts**: Cataracts are a common age-related condition in which the lens of the eye becomes cloudy, causing blurry vision and sensitivity to light. Surgery is the most common treatment for cataracts.  

<img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/cataract.jpg" width="128" height="128" />

**Diabetic Retinopathy**: Diabetic Retinopathy is a complication of diabetes that affects the retina and can lead to vision loss. High blood sugar levels can damage blood vessels in the retina and cause them to leak or swell, leading to vision problems.

<img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/diabetic_retinopathy.jpeg" width="128" height="128" />

**Glaucoma**: Glaucoma is a group of eye diseases that can damage the optic nerve and lead to vision loss. It is often caused by increased pressure in the eye, although not all cases of glaucoma have elevated eye pressure. Early detection and treatment are important in preventing vision loss from glaucoma, which has no cure.

<img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/glaucoma.jpg" width="128" height="128" />

**Normal**

<img src="https://github.com/SinaRaoufi/Eye-Diseases-Classification/blob/master/samples/normal.jpg" width="128" height="128" />



## Model
For this classification, I use a Convolutional neural network (CNN) which is made of convolution stages (Conv2d, ReLU, MaxPool2d) and a fully connected layer at the end.
