# CNN Assignment
> Our main objective is to build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. 

A solution which can evaluate images and alert the dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Contributors](#contributors)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
- The dataset consists of 2357 images of malignant and benign oncological diseases, which were formed from the International Skin Imaging Collaboration (ISIC). All images were sorted according to the classification taken with ISIC, and all subsets were divided into the same number of images, with the exception of melanomas and moles, whose images are slightly dominant.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->
## Technologies Used
- Python Pandas - version 1.1.5
- Python Numpy - version 1.19.5
- Python Seaborn - version 0.11.2
- Tensorflow 2.10.0
- Jupyter Notebook - version 6.4.10
- ipykernel - version 6.13.0

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->


## Conclusions
With the use of augmentor to balance the data among classes, I am able to achieve 81.96% validation accuracy with below structure of CNN.
Sequential([
    - rescaling
    - conv2d
    - MaxPool
    - conv2d
    - MaxPool
    - conv2d
    - MaxPool
    - Dropout
    - Flatten
    - Dense
    - Dense
    - Dense
])



<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Contributors
* [Shravan](https://github.com/simplyshravan)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
