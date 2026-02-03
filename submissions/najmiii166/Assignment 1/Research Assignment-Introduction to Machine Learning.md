# Research Assignment 1: Introduction to Machine Learning

## 1. Definition of Machine Learning (with a Real-Life Example)

Machine Learning (ML) is a branch of Artificial Intelligence that focuses on enabling computers to learn from data and improve their performance on a task without being explicitly programmed. Instead of following fixed rules written by a programmer, a machine learning system identifies patterns from historical data and uses those patterns to make predictions or decisions when new data is provided.

A common real-life example of machine learning is email spam filtering. Email systems learn from previously labeled emails (spam or not spam). Over time, the system improves its ability to correctly classify new incoming emails by learning patterns such as keywords, sender behavior, and message structure.

---

## 2. Supervised Learning vs Unsupervised Learning

Machine learning techniques can be broadly classified into supervised and unsupervised learning based on the type of data they use.

### Supervised Learning
Supervised learning uses labeled data, meaning each input is associated with a known correct output. The goal is to learn a mapping from inputs to outputs so the model can predict outcomes for new data.

**Example:** Predicting house prices based on features such as size, location, and number of rooms using past housing data where prices are already known.

### Unsupervised Learning
Unsupervised learning works with unlabeled data. The model tries to discover hidden patterns, groupings, or structures within the data without predefined outputs.

**Example:** Customer segmentation, where a business groups customers based on purchasing behavior without knowing the groups in advance.

---

## 3. Overfitting: Causes and Prevention

Overfitting occurs when a machine learning model learns the training data too well, including noise and irrelevant details. As a result, the model performs very well on training data but poorly on new, unseen data.

### Causes of Overfitting
- Using a model that is too complex for the dataset
- Having a small or noisy training dataset
- Training the model for too long

### Prevention Methods
- Using cross-validation to evaluate model performance
- Applying regularization techniques to reduce model complexity
- Increasing the size and quality of the training dataset
- Stopping training early when performance starts to degrade

---

## 4. Training Data and Test Data Split

In machine learning, data is commonly divided into training data and test data. The training data is used to teach the model, while the test data is used to evaluate how well the model performs on unseen data.

A common split ratio is 80% for training and 20% for testing. This process is necessary to ensure that the model generalizes well and does not simply memorize the training data.

---

## 5. Case Study: Application of Machine Learning in Healthcare

Machine learning has been widely applied in healthcare to improve disease detection and diagnosis. One notable example is the use of deep learning models to detect diabetic retinopathy from retinal images.

In this case, machine learning models are trained on large datasets of labeled eye images. The trained system can then identify signs of the disease with high accuracy, helping doctors detect conditions earlier and reduce the workload on medical professionals.

This application demonstrates how machine learning can enhance decision-making and improve patient outcomes when used responsibly.

---

## References

1. Mitchell, T. M. (1997). *Machine Learning*. McGraw-Hill.
2. Google Research. (2016). Deep Learning for Detection of Diabetic Retinopathy.
3. Alpaydin, E. (2020). *Introduction to Machine Learning*. MIT Press.
