
# Resume Classifier

* This repository represents "Resume Classifier using DenseNet".
* With the help of this project we can classify resumes among different documents. 

## Description

This project involves creating a model which identifies whether a document image is a resume or not, using only the visual representations of an image.

## Dataset

The dataset, processed from diverse sources including Kaggle's Real World Documents Collections, was carefully prepared for accuracy. After manual curation, the training set was categorized into resume and non-resume images, followed by data augmentation for enhanced model training diversity. The dataset is available in the repository.


## Model Selected
DenseNet has been selected for this particular task due to its strong feature reuse, parameter efficiency, intra-layer communication for complex relationships, effective feature learning, and benefits in reusing features for improved performance over VGG16, InceptionV3, and Vision Transformer.

In your Python notebook, import and load the model:

```python
from tensorflow.keras.applications import DenseNet121
model = DenseNet121(weights='imagenet')
```


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

Numpy  1.19.5\
Pandas 1.3.3\
Matplotlib 3.4.3\
Seaborn 0.11.2\
Pillow 8.3.2\
Scikit-learn 0.24.2\
Tensorflow 2.7.0\
Keras 2.8.0\
ImageIO 2.9.0





## Documentation

Follow the below link to read documentation\
* [Documentation](https://docs.google.com/document/d/1tl5WYWkwprbBwB5JMcyYXasWcSQm7cWlb5-y5ccPt0k/edit?usp=sharing)

