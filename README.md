In this repo you will find a collection of Machine Learning models I have learned independently during my final year of university and first years as an Engineer.

You can find the theoretical aspects of ML models, some related algorithms, as well as their implementation from scratch, and their use in sklearn on real datasets. 

# Resources
I will be using the following resources during my learning:

- Hands-on Machine Learning
- An Introduction to Statistical Learning
- The Elements of Statistical Learning

- Python Data Science Handbook 
- Understanding Machine Learning: From Theory to Algorithms 

# Roadmap
Assuming you have a good level of:
- Mathematics
- Statistics
- Python
- Numpy
- Pandas
And know something of seaborn / matplotlib, you can start this roadmap. 

It is divided into specified chapters about a single model, where you can learn about the model and general Machine Learning concepts associated with it, interleaving practice with theory.

It is important to develop on each step a practical projecto to apply the learned concepts, in order to test you knowledge.

## 1. Foundations and Clasification
### Linear Regression
- Linear Regression Model
- Train/Test Split
- Outlier Detection: IQR, Z-score, Modified Z-score
- Missing values (basic)
- Encoding (basic)
- Feature Scaling (basic)
- Transformations (Log, Box-Cox, Yeo-Johnson)
- Transformation Pipelines & Data Leakage
- Regression Metrics (MAE, MSE, RMSE, R^2)
- Project with a Linear Regression Model

### Polynomial Regression
- Example proving Linear Regression is not everything
- Polynomial Features
- Underfitting vs Overfitting
- Bias-Variance Tradeoff
- Learning Curves
- Regularization (Ridge, Lasso, Elastic Net)
- Project with Polynomial Regression

### Logisctic Regression
- Logistic Regression Model
- Clasification with logistic regression
- Softmax Regression Model
- Classification Metrics (Accuracy, Precission, Recall, F1)
- ROC-AUC
- Confusion Matrix
- Project with Logistic Regression

### Model Selection & Evaluation
- Cross Validation
- StratifiedCV
- GridSearchCV
- RandomSearchCV
- NestedCV
- Validation Curves
- Example of Model Selection

## 2. Distances and Probability Models
### Naive Bayes
- Naive Bayes Model
- Text Preprocessing
- Bag of Words
- TF-IDF
- NLP?
- Project with Naive Bayes

### K-Nearest Neighbors (KNN)
- KNN Model
- Curse of Dimensionality
- Transformations & Scale sensibility
- Outlier Detection (KNN-based)
- Missing Values Inputing
- Local Outlier Factor (LOF)
- Example with KNN

### SVM
- SVM Models
- Transformations & Feature Scaling (Why SVM is sensible to feature scaling?)
- Kernels (Lienar, RBF, Poly)
- Hyperparameter Tuning (C, Gamma)
- Projects with SVM

## 3. Trees, Ensembles and Standards
### Decission Trees
- Decission Tree Model
- Feature Importance
- Overfitting (on trees)
- Pruning
- Projects with Decission Trees

### Ensemble Methods
- Bagging vs Boosting vs Stacking

### Random Forest
- Random Forest Models
- Feature Engineering & OutlierTrimmer
- Transformations don't affect them
- Feature Selection
- Permutation Importance
- SHAP (Advanced Interpretability)
- SMOTE, under/oversampling, class weights
- Projects with Random Forests

### XGBoost / LightGBM (Boosting on Production)
- XGBoost & LightGBM
- Early Stopping
- Tuning pipeline from start to end
- Optuna (Advanced Bayesian Tuning)

## 4. Unsupervised Learning
### Isolation Forest 
- Isolation Forest Model
- Outlier Detection (advanced)

### PCA
- PCA algorithm
- Explicated variance
- Solving Curse of Dimensionality
- Examples with PCA

### K-Means
- K-Means for clustering
- Silhouette Score & Elbow Method
- Examples with K-Means

### Hierarchical Clustering
- Hierarchical Clustering
- Dendograms

### DBSCAN
- DBSCAN algorithm
- Density-based clustering
- Outlier detection (noise)
- Examples with DBSCAN

## 5. Deep Learning
### Neural Networks
- Perceptron 
- Neural Network
- Backpropagation
- Batching & Epocs
- GPU vs CPU
- Data augmentation (intro)
- Projects with NN

### CNN
- CNN Model
- Image Preprocessing
- Transfer Learning
- Projects with CNN

### RNN
- RNN Model
- Short-time Memory Problem
- Projects with RNN

### LSTM & GRU
- Memory problems of RNN
- LSTM Model
- GRU Model

### Transformers
- Tokenization
- Embeddings
- Attention Mechanism

### GAN (Generative Adversarial Networks)
- GAN

### Reinforcement Learning
- RL

## 6. MLOps
- Tracking, MLflow
- Deployment
- Model Monitoring

