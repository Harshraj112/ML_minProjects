# 🤖 Machine Learning Mini Projects

A comprehensive collection of machine learning projects covering supervised learning, unsupervised learning, natural language processing, and complete ML project implementations.

## 📁 Repository Structure

This repository contains **17+ machine learning projects** organized by algorithm and technique:

```
ML_miniProjects/
├── Adaboost/                      # AdaBoost classification & regression
├── Anomaly Detection/             # Anomaly detection techniques
├── CompleteNLP For Machine Learning/  # Complete NLP practicals & projects
├── DBSCAN/                        # Density-based clustering
├── Decision Tree/                 # Decision tree classifier & regressor
├── GBoost/                        # Gradient Boosting implementations
├── Hierarical Clustering/         # Hierarchical clustering analysis
├── K Means/                       # K-Means clustering
├── K Nearest Neighour/            # KNN algorithm implementations
├── Linear Regression/             # Various regression techniques
├── Logistic/                      # Logistic regression
├── NLP/                           # Natural Language Processing projects
├── PCA/                           # Principal Component Analysis
├── Random Forest/                 # Random Forest ensemble methods
├── Ridge Lasso/                   # Regularization techniques
├── SVM/                           # Support Vector Machines
├── Xgboost/                       # XGBoost implementations
├── Step By Step Project Implementation With LifeCycle Of ML Projects/
└── Dataset/                       # Shared datasets
```

## 🎯 Projects Overview

### 📊 Supervised Learning

#### 1. **Linear Regression** (23 files)
Comprehensive regression analysis including:
- Simple and Multiple Linear Regression
- Polynomial Regression
- Ridge & Lasso Regression
- Handling Imbalanced Datasets
- **Projects:**
  - Algerian Forest Fires Prediction
  - Economic Index Analysis
  - Height-Weight Prediction
  - QCM Sensor Alcohol Dataset Analysis

#### 2. **Logistic Regression**
Binary and multiclass classification implementations

#### 3. **Decision Tree**
- Decision Tree Classifier Implementation
- Diabetes Prediction using Decision Tree Regressor

#### 4. **K-Nearest Neighbors (KNN)**
Distance-based classification and regression

#### 5. **Support Vector Machines (SVM)** (3 files)
Kernel-based classification techniques

#### 6. **Ridge & Lasso Regression** (4 files)
L1 and L2 regularization for preventing overfitting

### 🌳 Ensemble Methods

#### 7. **Random Forest** (4 files)
Bagging-based ensemble learning

#### 8. **AdaBoost**
Adaptive boosting for classification and regression
- Travel Package Purchase Prediction
- Used Car Price Prediction

#### 9. **Gradient Boosting (GBoost)**
Sequential ensemble techniques

#### 10. **XGBoost**
Extreme gradient boosting implementations

### 🔍 Unsupervised Learning

#### 11. **K-Means Clustering**
Partitioning-based clustering algorithm

#### 12. **Hierarchical Clustering**
Agglomerative and divisive clustering methods

#### 13. **DBSCAN**
Density-Based Spatial Clustering with Noise

#### 14. **Principal Component Analysis (PCA)**
Dimensionality reduction and feature extraction

### 🚨 Anomaly Detection (3 files)
- Isolation Forest for Anomaly Detection
- DBSCAN-based Anomaly Detection
- Healthcare dataset analysis

### 💬 Natural Language Processing (17 files)

**Text Preprocessing:**
- Tokenization using NLTK
- Stemming and Lemmatization
- Stopwords Removal
- Parts of Speech (POS) Tagging
- Named Entity Recognition (NER)

**Feature Extraction:**
- Bag of Words (BOW)
- TF-IDF (Term Frequency-Inverse Document Frequency)
- Word2Vec
- Average Word2Vec

**NLP Projects:**
- **Spam/Ham Email Classification** (Multiple implementations)
  - Using TF-IDF + Machine Learning
  - Using BOW + Machine Learning
  - Using Word2Vec + Machine Learning
- **Kindle Review Sentiment Analysis**

### 📚 CompleteNLP For Machine Learning (13 files)

A comprehensive collection of NLP practicals and projects covering fundamental to advanced concepts:

**Text Preprocessing Fundamentals:**
- **Tokenization Example Using NLTK** - Breaking text into tokens
- **Stemming And Its Types** - Text normalization techniques
- **Lemmatization** - Converting words to their base forms
- **Text Preprocessing-Stopwords With NLTK** - Removing common words
- **Parts Of Speech Tagging** - Grammatical classification
- **Named Entity Recognition** - Identifying and classifying entities

**Feature Engineering:**
- **Bag Of Words Practicals** (File 15) - BOW implementation
- **TF-IDF Practical** (File 16) - Term frequency analysis
- **Word2Vec Practical Implementation** (File 26) - Word embeddings

**Applied NLP Projects:**
- **Spam Ham Classification Using TF-IDF And ML** (File 27)
- **Spam Ham Classification Using BOW And TFIDF And ML** (File 27.2)
- **Spam Ham Projects Using Word2vec, AvgWord2vec** (Files 28 & 29)
- **Kindle Review Sentiment Analysis** (Files 30 & 31)


### 🔄 Complete ML Project Lifecycle
End-to-end implementation covering:
- Problem definition and data collection
- Exploratory Data Analysis (EDA)
- Feature engineering
- Model training and evaluation
- Model deployment strategies

## 🛠️ Technologies & Tools

### Core Libraries
- **Python 3.x**
- **NumPy** - Numerical computing
- **Pandas** - Data manipulation and analysis
- **Matplotlib** - Data visualization
- **Seaborn** - Statistical visualization

### Machine Learning
- **scikit-learn** - ML algorithms and tools
- **XGBoost** - Gradient boosting framework
- **NLTK** - Natural Language Toolkit
- **SpaCy** - Industrial-strength NLP

### Development Environment
- **Jupyter Notebook** - Interactive development
- **Conda** - Environment management

## 🚀 Getting Started

### Prerequisites

1. **Install Python 3.x** from [python.org](https://www.python.org/)

2. **Install required libraries:**

```bash
# Core libraries
pip install numpy pandas matplotlib seaborn

# Machine learning
pip install scikit-learn xgboost

# NLP libraries
pip install nltk spacy

# Notebook environment
pip install jupyter notebook
```

3. **Download NLTK data (for NLP projects):**

```python
import nltk
nltk.download('punkt')
nltk.download('stopwords')
nltk.download('wordnet')
nltk.download('averaged_perceptron_tagger')
```

### Running the Projects

1. Clone or download this repository
2. Navigate to the ML_miniProjects directory
3. Start Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
4. Browse to any project folder and open the `.ipynb` files
5. Run cells sequentially to execute the code

## 📚 Key Concepts Covered

### Algorithms
- Linear & Polynomial Regression
- Logistic Regression
- Decision Trees
- Random Forests
- Support Vector Machines
- K-Nearest Neighbors
- AdaBoost, Gradient Boosting, XGBoost
- K-Means, Hierarchical Clustering, DBSCAN
- PCA for dimensionality reduction
- Anomaly detection techniques

### Machine Learning Techniques
- Train-test splitting
- Cross-validation
- Hyperparameter tuning
- Feature engineering
- Feature scaling and normalization
- Handling imbalanced datasets
- Regularization (L1/L2)
- Ensemble methods (Bagging, Boosting)

### NLP Techniques
- Text preprocessing and cleaning
- Tokenization
- Stemming and Lemmatization
- Feature extraction (BOW, TF-IDF, Word2Vec)
- Text classification
- Sentiment analysis

### Evaluation Metrics
**Classification:**
- Accuracy, Precision, Recall, F1-Score
- Confusion Matrix
- ROC-AUC Score

**Regression:**
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

**Clustering:**
- Silhouette Score
- Inertia
- Davies-Bouldin Index

## 📈 Project Highlights

### 🏆 Featured Projects

1. **Spam Email Classification** - Multiple approaches using BOW, TF-IDF, and Word2Vec
2. **Kindle Review Sentiment Analysis** - NLP-based sentiment classification
3. **Algerian Forest Fires Prediction** - Regression analysis for fire risk
4. **Travel Package Prediction** - Customer behavior analysis using AdaBoost
5. **Used Car Price Prediction** - Regression with ensemble methods
6. **Diabetes Prediction** - Healthcare analytics using Decision Trees
7. **Healthcare Anomaly Detection** - Identifying outliers in medical data

## 📝 Best Practices Implemented

- Clean, well-documented code
- Exploratory data analysis before modeling
- Proper train-test splitting (avoiding data leakage)
- Model evaluation using multiple metrics
- Visualization of results
- Handling missing values and outliers
- Feature engineering and selection

## 🎓 Learning Path

**Beginners:** Start with:
1. Linear Regression projects
2. Logistic Regression
3. Decision Trees
4. K-Means Clustering

**Intermediate:** Progress to:
1. Ensemble methods (Random Forest, AdaBoost)
2. SVM implementations
3. NLP text preprocessing
4. PCA and dimensionality reduction

**Advanced:** Explore:
1. XGBoost and Gradient Boosting
2. Complete NLP projects (Spam classification, Sentiment analysis)
3. Anomaly Detection
4. Full ML project lifecycle implementation

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Add new machine learning projects
- Improve existing implementations
- Fix bugs or optimize code
- Add documentation and examples

## 📄 License

This repository is open-source and available for educational purposes.

## 📧 Contact

**Author:** Harsh Raj  
**Repository:** ML_miniProjects  
**Last Updated:** December 2025

---

⭐ **If you find this repository helpful, please consider giving it a star!**

## 🔗 Quick Links

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [NLTK Documentation](https://www.nltk.org/)
- [XGBoost Documentation](https://xgboost.readthedocs.io/)
- [Pandas Documentation](https://pandas.pydata.org/)
- [Jupyter Notebook](https://jupyter.org/)
