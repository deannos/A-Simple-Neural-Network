# SNN 

*SNN - A simple Neural Network . Here I worked on Training a neural network to perform a simple classification.*


## Documentation

- **Classification**  :-Classification is a supervised machine learning process of categorizing a given set of input data into classes based on one or more variables. Additionally, a classification problem can be performed on structured and unstructured data to accurately predict whether or not the data will fall into predetermined categories. 

Classification in machine learning can require two or more categories of a given data set. Therefore, it generates a probability score to assign the data into a specific category, such as spam or not spam, yes or no, disease or no disease, red or green, male or female, etc.   

Some Applications of Machine Learning Classification Problems:-
-Image classification 
 -Fraud detection
-Document classification 
-Spam filtering  
-Facial recognition
-Voice recognition 
-Medical diagnostic test 
-Customer behavior prediction 
-Product categorization
-Malware classification
-Types of Classification Tasks in Machine Learning


**Classification Predictive Modeling**
In machine learning, classification is a predictive modeling problem where the class label is anticipated for a specific example of input data. For example, in determining handwriting characters, identifying spam, and so on, the classification requires training data with a large number of datasets of input and output. The most common classification algorithms are binary classification, multi-class classification, multi-label classification, and imbalanced classification, which are described below.

**Binary Classification**
Binary is a type of problem in classification in machine learning that has only two possible outcomes. For example, yes or no, true or false, spam or not spam, etc. Some common binary classification algorithms are logistic regression, decision trees, simple bayes, and support vector machines. 

**Multi-Class Classification**
Multi-class is a type of classification problem with more than two outcomes and does not have the concept of normal and abnormal outcomes. Here each outcome is assigned to only one label. For example, classifying images, classifying species, and categorizing faces, among others. Some common multi-class algorithms are choice trees, progressive boosting, nearest k neighbors, and rough forest. 

**Multi-Label Classification**
Multi-label is a type of classification problem that may have more than one class label assigned to the data. Here the model will have multiple outcomes. For example, a book or a movie can be categorized into multiple genres, or an image can have multiple objects. Some common multi-label algorithms are multi-label decision trees, multi-label gradient boosting, and multi-label random forests. 

**What is a Classification Algorithm?**
A classification algorithm is a supervised learning technique that uses data training to determine data into different classes. Classification predictive modeling is trained using data or observations, and new observations are categorized into classes or groups. Classification predictive modeling is the task of a mapping function (f) from input variables (x) to discrete output variables (y). In this approach, the algorithm generates a probability score and assigns this score to the input. For example, email service providers use classification to generate probability scores for email identification to determine if the email is in the spam class or not. 

*Learners in Classification Problems*:-

**Lazy Learners**
Lazy learners store the training data and wait until a testing dataset appears. The primary aim of lazy learning is to continuously update the dataset with new entries. However, as the data is continually updated, it becomes outdated frequently. Thus, these algorithms take comparatively less time to train and more time to predict. Lazy learning algorithms are beneficial when working with large, changing datasets with a smaller set of queried attributes. Lazy learning is easy to maintain and can be applied to multiple problems. Some examples of lazy learners include local regression, lazy bayesian rules and k-nearest neighbor (KNN) algorithm, instance-based learning, and case-based reasoning.

**Eager Learners**
Eager learners construct a classification layer before receiving the training and testing the dataset. Before it observes the input queries, eager learning builds an explicit description of the training function based on the training data. Because it is building a classification model, eager learning takes more time to train the dataset and less time to predict as compared to the lazy learning system. Eager learning is required to commit to a single hypothesis that covers the entire instance space. Some examples of eager learners include decision trees, naive Bayes, and **artificial neural networks (ANN)**. 

Let’s implement feedforward for our neural network. Here’s the image of the network again for reference:

![](https://miro.medium.com/v2/resize:fit:720/format:webp/1*x6KWjKTOBhUYL0MRX4M3oQ.png)


## Tech

- [C++] - high level programming language 
- [Visual studio Code ] - IDE 
- [SFML] - a simple, fast, cross-platform and object-oriented multimedia API.

## References

- https://towardsdatascience.com/machine-learning-for-beginners-an-introduction-to-neural-networks-d49f22d238f9








