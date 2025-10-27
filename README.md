This project is about Deep Learning and image analysis. It use Python as language, Tensorflow and Keras to build the model and matplotlib to visualize performance metrics.

The goal is to create a model that can predict if the image contains a plane. The dataset, available on Kaggle consist of 8000 images with a plane on it and 24000 without.

The images are 20x20 pixel squares and each pixel équals to 3 meters in reality. The data are stored in a JSON file organized chanel by chanel.
One array for each color (red, green and blue).

Source : https://www.kaggle.com/datasets/rhammell/planesnet.

You can find the way the model is build in the file plane_detection.ipynb
