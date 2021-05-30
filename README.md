# dog cat classification

a keras implementation of simple cnn model based 2 classes(dog, cat) classification on supervised learning.

## requirements

keras 2.2.4

matplotlib 3.4.2

numpy 1.20.1

opencv-python 4.5.2.52

python 3.7.10

scikit-learn 0.24.2

tensorflow 2.1.0

anaconda 3

pycharm

## datasets

train dataset contains 25000 images in 2 different classes(dog, cat).

there are 12500 images of each class.

test dataset contains 12500 images in 2 different classes(dog, cat).

### train

25000 images, 2 classes(dog, cat)

data augmentation - rescale, width shift, height shift, horizontal flip

### test

dog - 6303 images

cat - 6197 images

data augmentation - rescale

## Usage

### data preprocessing

dog_cat_preprocessing.py

### train

dog_cat.py

### test

dog_cat_test.py
