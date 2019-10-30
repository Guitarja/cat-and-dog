# cat-and-dog classification project
# Using data from https://www.kaggle.com/c/dogs-vs-cats/data
# Data storage structure: 
### train -> cat -> cat pictures
### ..... -> dog -> dog pictures
### validation -> cat pictures
### .......... -> dog pictures
### test -> unlabeled cat and dog pictures
## By increasing validation_steps, the model will have a smoother val_binary_crossentropy curve
