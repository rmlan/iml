# Handwritten Character recognition with CNN
## Segmentation and augmentation
The data acquisition and augmentation process is described in the corresponding jupyter notebook.

## Convolutional Neural Networks
In the main.ipynb file, the augmented data and the one linked in the project list on moodle are imported. The data obtained from the scanned sheets is used for training (consisting of 28k images), while about 30k images of the downloaded data (15% of the total) is used for testing during training. The performance of the CNNs on this smaller portion is identical to that on the rest. Two networks were trained, both achieving a similar performance on the downloaded dataset, with accuracy around 60%, despite having vastly different training times. In the more complex network, I tried to prevent overfitting by using more aggressive dropout coefficients.