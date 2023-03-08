# Road Signal Classification Model using TensorFlow

The goal of this project is to develop a deep learning model using VGG16-CNN architecture that can accurately classify and predict road signs. The model will be trained on a dataset of road sign images and corresponding labels.

## Dataset

The dataset used for this project can be downloaded from this [link](https://d17h27t6h515a5.cloudfront.net/topher/2017/February/5898cd6f_traffic-signs-data/traffic-signs-data.zip). The dataset consists of 43 different classes of road signs, with a total of 39,209 images.

## Labels

The labels for the dataset can be accessed via this [link](https://docs.google.com/document/d/1KlavfVAerQFibtuNL7HEZUitXwRK4oNbiYXd0pRIzjQ/edit?usp=sharing). The labels consist of the class ID and class name for each of the 43 different road sign classes.

## Website

Additional information about the dataset, including benchmark results, can be found on the [website](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset).

## Model Architecture

The VGG16-CNN architecture will be used as the basis for the model. The model will consist of several convolutional layers followed by fully connected layers, with dropout regularization to prevent overfitting.

## Training and Testing

The dataset will be divided into training, validation, and testing sets. The model will be trained on the training set and evaluated on the validation set. The final performance of the model will be evaluated on the testing set.

## Dependencies

The project will be implemented using TensorFlow, a popular deep learning framework. Other necessary dependencies include NumPy, Matplotlib, and OpenCV.

## References

1. K. Simonyan and A. Zisserman, "Very Deep Convolutional Networks for Large-Scale Image Recognition," arXiv:1409.1556, 2014.
2. TensorFlow: https://www.tensorflow.org/
3. NumPy: https://numpy.org/
4. Matplotlib: https://matplotlib.org/
5. OpenCV: https://opencv.org/
