# Marine-animal-classifier
Use of python deep learning (CNNs) , classify the given image of a marine animal into classes.
This GitHub repository is dedicated to the application of Convolutional Neural Networks (CNN) for the precise classification of marine life. my deep learning model has been trained on a diverse dataset of marine animals, enabling accurate identification and categorization. Dive into the world of marine biology and explore the power of CNN in understanding and preserving marine ecosystems. 🌊🐠🦈
This is just a basic implementation of CNNs for multiclass classification with upto 97% accuracy in training. however, the accuracy of classification on unseen data is not upto the mark,one of the reason may be insufficient training which can be fixed by-

1. Increasing the number of epochs to find the convergence point (make sure to not keep the number very high as it can cause overfitting of the model).
2. Changing the dataset - if you find a more comprehensive and more diverse dataset, it will make the learning of the model better and more accurate.
3. changing the model architecture - the model uses a very simple i.e basic CNN architecture, you can tweak the architecture (add more layers or change the pooling technique, activation function etc) to maybe improve the accuracy or efficiency of the output
