# Support-Vector-Machines-SVM
A Support Vector Machine (SVM) is a supervised machine learning algorithm that finds an optimal line or hyperplane to separate data into classes for classification, or to predict a continuous value for regression. Its primary goal is to maximize the margin, which is the distance between the hyperplane and the closest data points from either side. SVMs are versatile and can handle both linear and non-linear data through the use of kernel functions, which implicitly transform the data into a higher dimension to find a separating hyperplane.
## How it works
### Hyperplane: 
The decision boundary is the hyperplane that separates the data into different classes. In a 2D space, this is a line; in a 3D space, it's a plane; and in higher dimensions, it's a hyperplane. 
### Margin: 
The margin is the space between the hyperplane and the nearest data points on either side. SVMs aim to find the hyperplane with the largest possible margin to improve generalization. 
### Support Vectors: 
These are the data points that are closest to the hyperplane and are crucial for defining the margin and the hyperplane itself. The algorithm is memory-efficient because it only needs these support vectors to define the decision boundary. 
### Kernels: 
For non-linearly separable data, SVMs use kernel functions to map the data into a higher dimension where a linear hyperplane can be found. Common kernel types include linear, polynomial, and radial basis function (RBF). 

## Applications
### Image and speech recognition: 
Used in applications like facial recognition and voice command assistants. 
### Text classification: 
Common in natural language processing for tasks such as spam detection and sentiment analysis. 
### Medical and financial analysis: 
Employed in medical imaging, classification, and financial forecasting. 

# Resources
[What are Support Vector Machines](https://www.ibm.com/think/topics/support-vector-machine)

[Support Vector Machines (SVM): An Intuitive Explanation](https://medium.com/low-code-for-advanced-data-science/support-vector-machines-svm-an-intuitive-explanation-b084d6238106)
