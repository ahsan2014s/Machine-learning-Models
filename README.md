# Traditional Machine Learning Models

This repository contains optimized implementations of several foundational **traditional machine learning algorithms**. These models are essential building blocks for statistical pattern recognition and are widely used across various domains such as natural language processing, bioinformatics, and finance. Traditional ML models works best on structured data. They provide intuitions for Deep learning models as a baseline model while analyzing structured data. All the models and their accuracy tested on Irish datasset.

## Models Implemented so far:

### 1. Naive Bayes
A probabilistic classifier based on Bayes' Theorem with the "naive" assumption of feature independence. It is particularly effective for high-dimensional input data like text classification.

**Implementations:**
- Optimized for performance and scalability
- Supports Gaussian, Multinomial, and Bernoulli variants
- Suitable for real-time inference


### 2. Random Forest
An ensemble method using multiple decision trees to improve classification accuracy and control overfitting.

**Implementations:**
- Parallelized tree building
- Feature importance extraction
- Handles missing values and categorical data

---

### 3. Support Vector Machine (SVM)
A powerful classifier that finds the optimal hyperplane to separate classes with maximum margin.

**Implementations:**
- Kernel trick support (linear, polynomial, RBF, etc.)
- Multi-class classification via one-vs-rest
- Optimized using SMO algorithm

---

### 4. Hidden Markov Model (HMM)
A statistical model for sequential data, where the system is modeled as a Markov process with unobserved (hidden) states.

**Implementations:**
- Forward-backward algorithm
- Viterbi decoding
- Suitable for time-series and speech recognition


### 5.Optimized KNN Implementation:

**Implementations:**
- Uses GridSearchCV to find the optimal K value and other hyperparameters
- Tests different distance metrics (Manhattan and Euclidean)
- Evaluates different weighting schemes (uniform and distance-based)
- Compares different algorithms (ball_tree, kd_tree, brute force)
- Parallel processing for faster optimization

---

##  Download

_After copying the repository, unzip, go to google colab, open with google colab_
