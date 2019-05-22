# Dog-Breed-Classifer:

CNN Project [Udacity Deep Learning Nanodegree]

This is a repo for the Dog Breed Classifier Project in Udacity Nanodegree  It is implemented by using PyTorch library.
The classifier was trained on real world images and attempts to classify images as either human or dog. In the case of a dog the
the image is then classifies the most likely breed, and prints the probability. If a human is found the classifier returns the 
dog breed the human most resembles. 

The project took two approaches one using a neural network built from scratch. This was a challenge as identifying the right
architecture was time consuming and the resulting accuracy was quite low. Using transfer learning was far more successful. 
A VGG16 model was chosen which achieved much higher test accuracy and lower validation loss. The Classifier layer was modified to account for the number of dog breeds. 

The classifier will classify an image as either a dog or a human and then estimate the associated probability with a specific breed.

![alex](https://user-images.githubusercontent.com/39443902/58206637-ffeccd00-7cd8-11e9-852d-9d83f2910568.png)
It's a human and you look like:
Komondor with probability 1.81%
