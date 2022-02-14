In this notebook, I propose an original implementation from scratch of an image classifier on the Intel dataset (https://www.kaggle.com/puneet6060/intel-image-classification). This dataset is composed of about 17k images belonging to different 6 classes.

The algorithm achieves more than 90% accuracy on the test set (see the last output of the notebook for exact accuracy).

First, we explore the data and create a data generator with data augmentation. Then we train and evaluate two different models:
- a CNN network with 3 convolutional layers
- a pre-trained Inceptionv3 model (https://www.kaggle.com/google-brain/inception-v3) followed by a dense NN with 3 layers
