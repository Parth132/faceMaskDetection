# Face Mask Detection using Deep Learning
The face mask detection project is a deep learning and computer vision application that detects whether a person is wearing a face mask or not. The project is built using the TensorFlow framework and a pre-trained MobileNetV2 architecture.

The repository contains the following files:

1. `dataset`: This folder contains the training and testing datasets used to train the face mask detection model. The dataset consists of two classes, one for images of people wearing masks and another for images of people not wearing masks.

2. `models`: This folder contains the script used to train the face mask detection model. The script uses the MobileNetV2 architecture as a pre-trained model and fine-tunes it on the face mask dataset.

3. `test_images`: This folder contains a set of test images used to evaluate the performance of the trained face mask detection model.

4. `utils`: This folder contains a script for generating augmented images from the training dataset. The script uses various image augmentation techniques to generate additional training data and improve the accuracy of the model.

5. `results`: This folder contains the output of the trained model on the test images.

The face mask detection model is trained using the TensorFlow framework and the MobileNetV2 architecture. The training script takes the face mask dataset as input and fine-tunes the pre-trained MobileNetV2 architecture to classify images as either wearing masks or not wearing masks.

The face mask detection model is evaluated on a set of test images using metrics such as accuracy, precision, recall, and F1 score. The results are saved in the `results` folder.
