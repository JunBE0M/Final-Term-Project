# Final-Term-Project
---
### Project Description
This project was created to solve the classification problem by utilizing the scikit learn library. In this project, I use a machine learning algorithm called a perceptron to find the best model for a classification problem. In the code written in the project, there are some explanation of the dataset of face recognition, the process of finding the best model, and outputting the accuracy of the model.

---
### DataSet Description
In the code, I use the Olivetti faces dataset. This images are Face imagestaken between April 1992 and April 1994 at AT&T Laboratories Cambridge. The image is quantized to 256 grey levels and stored as unsigned 8-bit integers; the loader will convert these to floating point values on the interval [0, 1], which are easier to work with for many algorithms. The “target” for this database is an integer from 0 to 39 indicating the identity of the person pictured; however, with only 10 examples per class, this relatively small dataset is more interesting from an unsupervised or semi-supervised perspective. The original dataset consisted of 92 x 112, while the version available here consists of 64x64 images.

---
### Machine Learning Algorithm Description - Perceptron
The module scikit learn contains a Perceptron class. We saw that a perceptron is an algorithm to solve binary classifier problems. This means that a Perceptron is abinary classifier, which can decide whether or not an input belongs to one or the other class.

---
### The Hyperparameter Description
A model hyperparameter is a configuration that is external to the model and whose value cannot be estimated from data. In the code, I tuned some hyperparameters to find the best model for face recognition. 
