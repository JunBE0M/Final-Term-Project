# Final-Term-Project
---
### Project Description
This project was created to solve the classification problem by utilizing the scikit learn library. In this project, I use a machine learning algorithm called a logistic regression to find the best model for a classification problem. In the code written in the project, there are some explanation of the dataset of face recognition, the process of finding the best model, and outputting the accuracy of the model.

---
### DataSet Description
In the code, I use the Olivetti faces dataset. This images are Face imagestaken between April 1992 and April 1994 at AT&T Laboratories Cambridge. The image is quantized to 256 grey levels and stored as unsigned 8-bit integers; the loader will convert these to floating point values on the interval [0, 1], which are easier to work with for many algorithms. The “target” for this database is an integer from 0 to 39 indicating the identity of the person pictured; however, with only 10 examples per class, this relatively small dataset is more interesting from an unsupervised or semi-supervised perspective. The original dataset consisted of 92 x 112, while the version available here consists of 64x64 images.

---
### Machine Learning Algorithm Description - Logistic Regression
Logistic Regression is a Machine Learning classification algorithm that is used to predict the probability of a categorical dependent variable. In logistic regression, the dependent variable is a binary variable that contains data coded as 1 (yes, success, etc.) or 0 (no, failure, etc.).

---
### The Hyperparameter Description
A model hyperparameter is a configuration that is external to the model and whose value cannot be estimated from data. In the code, I tuned some hyperparameters to find the best model for face recognition. I first tuned 'C', one of the hyperparmenters of logistic regression algorithm, to 1000. The option ‘C’ is an inverse of regularization strength. By increasing the 'C' value, the model gave high weight to the training data. Next, I tuned 'tol' to 0.0000001. The option ‘tol’ indicates tolerance for stopping criteria. I lowered the value of 'tol' because there is a risk that the algorithm will not converge. Next, I tuned 'random_state' to 0. This hyperparameter controls the randomness of the algorithm. 
When random_state is 0, the test accuracy does not change. Finally I tuned the 'max_iter' to 1000. 'max_iter' means the maximum value of iteration. In the process of continuously tuning max_iter, I set 1000, which gives the highest model accuracy. There were many more hyperparmenters besides the ones I tuned, but I didn't put them in the code because they didn't have a big impact on the change in accuracy of the model.
```
  C = 1000.0
  tol = 0.0000001 
  random_state = 0 
  max_iter = 1000
```  
---
### License information
Final-Term-Project is licensed under the MIT License

---
### Contact Info
Email : jb020214@cau.ac.kr
