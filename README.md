# Image Classification with Keras
This is a simple Python script that demonstrates how to use Keras, a high-level neural network API, to load a pre-trained image classification model and use it to make predictions on a new image. The script uses a convolutional neural network (CNN) trained on the CIFAR-10 dataset, which includes 10 classes of images: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

**Getting Started**
To use this script, you will need to have Python 3 and the following libraries installed:

 - TensorFlow
 - Keras
 - NumPy
 - Pillow

You can install these libraries using pip:

    pip install tensorflow keras numpy pillow
    
**Usage**

To use the script, simply run the following command:
	        
	python predict.py
        
        
        
You will be prompted to enter the name of the image file you want to classify. The script will then load the image, preprocess it, and use the pre-trained model to make a prediction. The predicted class will be displayed on the console.
