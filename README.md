# Machine Learning Projects

My comprehensive collection of machine learning, deep learning, and NLP projects covering concepts from statistics and Python programming to advanced EDA, Machine Learning Models, NLP and transformer architectures.

---

## 📊 Maths

### Statistics 
- **Population vs. Sample**
- **Types of Variables**
  - Categorical: Nominal / Ordinal
  - Numerical: Discrete / Continuous
- **Descriptive Statistics**
- **Measures of Central Tendency**
  - (Mean, Median, Mode)
- **Measures of Dispersion**
  - (Range, Variance, Interquartile Range IQR)
- **Data Distribution and Visualization**
  - (Histograms, Box Plots)
- **Probability Basics**
  - (Definition, Random Events, Outcomes)
- **Probability Rules**
  - (Addition Rule, Multiplication Rule)
- **Conditional Probability**
- **Bayes' Theorem**
- **Inferential Statistics**
- **Sampling Distributions**
- **Central Limit Theorem (CLT)**
- **Hypothesis Testing**
  - (Null/Alternative Hypothesis, P-value, Significance Level)
- **Confidence Intervals**

### Linear Algebra 
- **Vectors and Matrices**
- **Operations on Vectors**
  - (Addition, Subtraction, Scalar Multiplication)
- **Matrix Operations**
  - (Multiplication, Determinant, Inverse, Transpose)
- **Types of Matrices**
  - (Square, Diagonal, Identity, Zero, Row, Symmetric)
- **Linear Transformations**
  - (Scaling, Rotation, Reflection)
- **Eigenvalues and Eigenvectors**

---

## 🐍 Python

### Data Structures and Control Flow
- **Data Containers**
  - (Lists, Tuples, Sets, Dictionaries)
- **Lists Operations**
  - (Indexing, Slicing, Adding/Removing Elements)
- **Control Flow**
  - (If, If-Else, If-Elif-Else, Nested If Statements)

### Loops with Practical Application
- **For Loops**
  - (Iterating over List, Range, String, Nested For Loops)
- **While Loops**
  - (Basic, Break, Continue, Infinite Loop)
- **Large Practical Application**
  - (Finding Maximum Value, Counting Vowels, Finding Common Elements, Sum of Digits, Drawing Patterns, Creating a Dictionary from Lists, Password Check, Multiplication Table)

### Functions
- **Defining and Using Functions**
  - (Parameters, Default Parameters, Returning Multiple Values, Docstrings)
- **Lambda Functions**
- **Recursive Functions**
  - (Factorial, Fibonacci)
- **Higher-Order Functions**
  - (Function as Argument, Returning a Function)
- **Practical Examples**
  - (Average of Numbers, Longest Word, Prime Check, Temperature Conversion, List of Squares, Uppercase Conversion, Total Price with Tax, Min/Max Values, Email Validation, Character Frequency)

### Object-Oriented Programming (OOP)
- **OOP Concepts**
  - (Classes, Objects, Attributes, Methods)
- **Defining Classes and Creating Objects**
- **Practical Examples**
  - (Product Class, Calculator Class, Student Management System, Bank Account, Voting System, Temperature Converter, Car Rental System)

---

## 📈 Preprocessing & Visualization

### Numpy
- **Creating Numpy Arrays**
  - (From List, Zeros, Ones, Range, Linspace, Random Values)
- **Checking Shape and Data Type**
- **Indexing and Slicing**
  - (1D and 2D Arrays)
- **Array Operations**
  - (Element-wise Addition, Dot Product for Matrix Multiplication)
- **Statistical Operations**
  - (Mean, Sum, Max, Min)
- **Practical Applications**
  - (Square Matrix, Diagonal Matrix, Identity Matrix, Upper/Lower Triangular Matrix, Symmetric Matrix, Transpose, Trace, Determinant, Inverse, Rank)

### Pandas
- **Creating Pandas Data Structures**
  - (Creating a Series, Creating a DataFrame from a Dictionary)
- **Viewing and Inspecting Data**
  - (head(), info(), describe())
- **Selecting and Filtering Data**
  - (Selecting Columns, Filtering Rows Based on Condition, Selecting Specific Rows and Columns using loc[])
- **Modifying Data**
  - (Updating Column Values, Dropping Columns)
- **Handling Missing Data**
  - (Detecting Missing Values with isnull(), Filling Missing Values with fillna(), Dropping Rows with dropna())
- **Grouping and Aggregation**
  - (groupby() for mean, apply() for custom functions)

### Matplotlib & Seaborn
- **Plotting with Matplotlib**
  - (Line Plot, Scatter Plot, Bar Chart, Histogram, Subplots)
- **Identifying Outliers**
  - (Box Plot, Scatter Plot, Histogram, Density Plot)
- **Plotting with Seaborn**
  - (Line Plot, Scatter Plot with Regression Line, Bar Plot, Box Plot, Heatmap)
- **Practical Visualization Examples**
  - (Line Plot for Trends, Scatter Plot for Relationships, Bar Plot for Categorical Data, Histogram for Distribution, Box Plot for Outliers, Violin Plot for Density, Pair Plot for Pairwise Relationships, Count Plot for Frequency)

---

## 🤖 Machine Learning

### Machine Learning Models
- **Types of Machine Learning**
  - (Supervised, Unsupervised, Reinforcement)
- **Supervised vs. Unsupervised**
- **(Classification vs. Regression)**
- **Linear Regression**
- **Simple Linear Regression**
- **Multiple Linear Regression**
- **Polynomial Regression**
- **Key Characteristics**
- **Cost Function**
  - (Mean Squared Error MSE)
- **Different Evaluation Metrics**
  - (MSE, MAE)
- **Gradient Descent**
  - (Purpose, Partial Derivatives, Parameter Update Rules, Learning Rate)

### Data Preprocessing for ML
- **Encoding**
  - (Label Encoding, One-Hot Encoding)
- **Scaling**
  - ( Standardization (Z-Score Scaling), Example Scenario)
- **Overfitting and Underfitting**
  - (Bias, Variance, Balancing Bias and Variance, Techniques to Reduce Overfitting, Regularization, Regularization Parameter Lambda, Types of Regularization L1 & L2)

### Classification Algorithms & Metrics
- **Logistic Regression**
  - (Probabilistic Output, S-Curve, Logistic/Sigmoid Function, Hypothesis, Decision Boundary)
- **Classification Metrics**
- **Confusion Matrix**
  - (TP, TN, FP, FN)
- **Accuracy**
- **Precision**
- **Recall**
  - (Sensitivity)
- **F1-Score**
- **ROC Curve and AUC**

### Tree-Based & Probabilistic Models
- **Decision Tree**
- **Key Concepts**
  - (Root Node, Leaf Nodes, Splitting, Pruning)
- **How to Determine the Best Split?**
  - (Node Impurity)
- **Gini Index**
  - (Gini Impurity)
- **Entropy**
  - (Information Gain)
- **Misclassification Error**
- **Summary of Measures of Node Impurity**
- **Decision Tree Analysis of Iris Flower Classification**
- **Naive Bayes**
- **Bayes' Theorem for Classification**
- **Types of Naive Bayes**
  - (Gaussian, Multinomial, Bernoulli)
- **Spam Classification Example**
  - (Word Histograms, Likelihood, Laplace Smoothing, Posterior Probability)
- **Advantages and Disadvantages of Naive Bayes**

### KNN & SVM
- **K-Nearest Neighbors (KNN)**
- **Example of KNN**
- **Distance Measures for KNN**
  - (Manhattan, Euclidean, Minkowski, Cosine, Hamming)
- **Selecting the Best Value for k**
  - (Grid Search, Elbow Method)
- **Advantages & Disadvantages of KNN**
- **Support Vector Machines (SVM)**
- **How SVM Works**
  - (Linear Separation, Support Vectors, Non-Linear Data)
- **Example of SVM**
  - (Linear SVM, Non-Linear SVM with Kernel Trick)
- **Advantages & Disadvantages of SVM**
- **KNN vs. SVM Comparison**

### Dimensionality & Feature Selection
- **The Curse of Dimensionality**
- **Problems Caused by High Dimensionality**
  - (Increased Computation, Sparsity, Overfitting, Redundant Features, Difficult Visualization, Distance Issues, Storage Concerns)
- **How Dimensionality Reduction Helps**
- **Feature Selection**
- **Feature Extraction/Projection Techniques**
  - (PCA, LDA, t-SNE, UMAP)
- **Filter Methods**
  - (Pearson's Correlation, Chi-Square Test, ANOVA)
- **Wrapper Methods**
  - (Recursive Feature Elimination RFE, Forward/Backward Selection)
- **Embedded Methods**
  - (Lasso, Ridge, Random Forest Feature Importance)
- **Dimension Reduction**
  - (Feature Extraction)
- **Categories of Feature Extraction**
  - (Linear: PCA/FA/ICA, Non-Linear: Kernel PCA/t-SNE/MDS/SOM/UMAP)
- **Variance and Standard Deviation**
- **Linear Transformation**
- **Matrix Rank**
- **Eigenvalues and Eigenvectors in PCA**
- **Pre-conditions to apply PCA**
  - (Scaling, Numerical Data)
- **Steps to perform PCA**
  - (Standardize, Covariance Matrix, Eigenvectors/Eigenvalues, Select K, Multiply)
- **How to Choose the Number of Components K**
  - (Explained Variance, Visualization, Elbow Method)
- **t-SNE Explanation and Steps**
- **Notes on Feature Selection, Encoding, and Scaling Order**

### Ensemble Methods (Bagging & Boosting)
- **Bagging**
  - (Bootstrap Aggregating)
- **Random Forest & Voting**
  - (Hard/Soft Voting)
- **Trade-offs and Performance**
- **Boosting**
- **AdaBoost**
  - (Adaptive Boosting) (How it works, Advantages/Disadvantages, Real-life analogy)
- **Gradient Boosting**
  - (How it works, Advantages/Disadvantages, Real-life analogy)
- **XGBoost**
  - (Extreme Gradient Boosting) (Key Improvements: Regularization, Parallelized Training, Tree Pruning, Handling Missing Data, Weighted Voting, Learning Rate)
- **Summary of Differences**
  - (AdaBoost vs. Gradient Boosting vs. XGBoost)
- **Practical Use Cases**

### Unsupervised Learning (Clustering)
- **Types of Clustering**
  - (Hard Clustering, Soft Clustering)
- **use cases**
- **K-Means Clustering**
- **Key Points**
  - (Centroid-based Clustering)
- **Steps in K-Means**
  - (Choose K, Initialize Centroids, Assignment Step, Update Step, Repeat, Convergence)
- **Stopping Criteria in K-Means**
  - (Euclidean Distance, Centroid, Inertia)
- **Elbow Method for Optimal K**
- **Advantages & Disadvantages of K-Means**
- **DBSCAN**
- **Types of Points**
  - (Core Points, Border Points, Noise Points/Outliers)
- **Input Parameters**
  - (Epsilon ε, min_samples)
- **Clustering Process**
- **Cluster Shapes**
- **Noise Handling**
- **Advantages & Disadvantages of DBSCAN**

---

## 🧠 Deep Learning & NLP

### Natural Language Processing (NLP) - Basics
- **Applications In NLP**
  - (Text Classification, Sentiment Analysis, Text Similarity, Text Summarization, Machine Translation, Chatbots)
- **NLP Pipeline**
  - (Data Acquisition, Text Cleaning and Extraction, Preprocessing, Text Representations, ML Model, Evaluation, Deployment, Monitor & Update)
- **Text Cleaning using Regex**
  - (Regular Expression)
- **RegEx Functions**
  - (findall, search, split, sub)
- **Match ranges in regex**
- **Metacharacters**
- **Tokenization**
  - (Sentence Tokenization, Word Tokenization)
- **Tokenization using NLTK**
- **Case folding using spaCy**
- **Stemming**
  - (Porter, Snowball, Lancaster)
- **Lemmatization**
  - (Using NLTK and SpaCy)
- **Stop word removal**
- **Part-of-speech tagging**
- **Named Entity Recognition (NER)**
- **Spell Correction**

### Text Representations
- **NLP Pipeline**
  - (Text Representations)
- **Bag of Words (BoW)**
- **Notes on BoW**
  - (Lowercasing, Stop Words)
- **Bag-of-Words using sklearn**
- **Disadvantages of Bag of Words**
- **N-GRAM**
- **TF-IDF**
  - (How it works, TF-IDF in sklearn)
- **One Hot Encoding**
  - (Problems with One Hot Encoding: Large Features, Sparse Matrix, No Semantic Preservation)
- **Word Embeddings**
- **Word Embedding Algorithms**
  - (Embedding Layer, Word2Vec)
- **Word2Vec**
  - (CBOW, Skip-gram)

### Recurrent Neural Networks (RNN) & LSTM
- **Sequences in the Wild**
- **Sequence Modeling Applications**
  - (one to one, one to many, many to one, many to many)
- **Comparison between RNN and ANN**
- **Recurrent Neural Network (RNN)**
  - (How it works, Tanh activation, Back Propagation Through Time BPTT)
- **Problems of RNN**
  - (Vanishing/Exploding Gradients, Loss of non-linearity, Reduced Expressive Power, Difficulty with Long Sequences, Slower Computation)
- **Long Short Term Memory (LSTM)**
  - (Sigmoid, Tanh, Forget Gate, Input Gate, Cell State, Output Gate)
- **Implementation on LSTM and RNN**

### Sequence-to-Sequence Models
- **RNN architectures**
  - (one-to-one, one-to-many, many-to-one, many-to-many, staggered many-to-many)
- **Sequence-to-sequence**
  - (seq2seq, Encoder, Decoder, Conditional Language Model)
- **A RNN Language Model**
  - (Advantages, Disadvantages, Training)
- **Challenges in Machine Translation**
  - (Word alignment, Word order structure, Adequacy vs fluency, Bias)
- **Neural Machine Translation (NMT)**
- **Training vs Inference**
- **Beam Search**
- **Evaluation with BLEU**
- **Bottleneck Problem**
- **Attention Mechanism**
  - (How it works, Sequence-to-sequence with attention)

### Transformers
- **Challenges of Sequence-to-Sequence Models and Their Solutions**
  - (Seq2Seq Architecture, Bottleneck Problem, Two Major Issues)
- **How Transformers Solve the Bottleneck Problem**
  - (Self-Attention Mechanism, Parallel Processing)
- **Attention**
  - (Attention Mechanism, How Attention Works)
- **Handling Sequential Data Using Convolutions vs. RNNs**
  - (1-D Convolutions, RNNs)
- **RNN-Based Sequence-to-Sequence Model**
  - (Limitations: Fixed-size context vector, Difficult to parallelize, Vanishing gradients)
- **The Birth of Transformers**
  - (Origins, How Attention Solved the Bottleneck Problem, Key Advantages: Parallelization, Handling long sequences)
- **The Building Blocks of the Transformer Architecture**
  - (Encoder and Decoder Structure, Context Vector and Attention)
- **Parallel Processing and Positional Encoding**
- **Input Embedding**
  - (Tokenization, Embedding)
- **Positional Encoding**
  - (Purpose, Calculation using Sinusoidal functions)
- **Encoder Block in the Transformer**
  - (Components: Positional Encoding, Multi-Head Attention, Layer Normalization, Feed-Forward Neural Network, Residual/Skip Connections)
- **Multi-Head Attention Process Explanation**
  - (Scaled Dot-Product Attention, Query/Key/Value, Steps: Tokenization/Embedding, Initial Weights, Dot Product of Q and K, Scaling, Softmax, Attention Output Calculation)
- **Cosine Similarity** 
- **Scaling in Self-Attention**
- **Self-Attention Mechanism with Scaling**
- **Multi-Head Self-Attention**
  - (Parallel processing, Key terminologies, Concatenation and linear transformation, Wide vs Narrow architecture)
- **Norm Layer**
  - (Normalization process, Importance: Faster training, Reduce bias, Prevents weight explosion, Difference between Layer Normalization and Batch Normalization)
- **Masked Head Attention**
- **Translation Scenario Using Transformers**
  - (Training phase, Inference phase, Greedy vs Beam Search)

---

## 📁 Repository Structure
