# Master-Thesis 
## "Classification of Stars, Galaxies and Quasars Based on Machine Learning Algorithms."  

# Purpose of the project
This master’s thesis focuses on technical parts, aspects of implementing data analysis and usage of machine learning algorithms to classify three groups of objects measured by astronomers. Alongside with Machine Learning algorithms implementation for specific described problem, analysis and comparison of the performance for each of the method is presented.  
There are a couple of astronomic institutes or other initiatives to measure and classify astrophysics objects from the “sky”. The process of classification from the human being perspective is time consuming and could be very inconsistent and not error prune. This process assumes to find out correlations between captured data from different angles, even resources. The huge amount of data does not facilitate the entire process. One of the possible solution to enable faster classification is to implement the new approach which is machine learning.  
# Objective
The main goal of this master’s thesis is to clearly depict which possible machine learning algorithms could be used in such a problem, what are the differences between them also how algorithms could highlight relevant information about the dataset that is under investigation.  
Nevertheless, the big part of machine learning implementation is data exploratory analysis. The first part of this dissertation focuses on dataset explanation. The resources where data is collected from, the main initiative of the sky survey, the description of the entire dataset.  
Next part is data preparation for further processing along with statistical analysis.  
After preparation the initial machine learning algorithms test takes place. Moreover, the explanation and comparison of few algorithms is included.  
There are also further thoughts on how this dissertation could be expanded on another similar real classification problem.

# Materials  
All code used to produce results is stored in MasterThesis.ipynb.  

# Example results  
## Deep Neural Network Hyperparameter tuning  
<img src="https://github.com/amasend/Master-Thesis/blob/master/Figures/Figure%2064.%20Deep%20Neural%20Network%20Training%20Validation%20Accuracy%20Scores%20for%20Different%20Parameters..png?raw=true"/>  

## ML Algorithms performance metrics in relation to training dataset size  
<p align="center">
<img src="https://github.com/amasend/Master-Thesis/blob/master/Figures/Figure%2070.%20Learning%20Curves%20for%20Each%20ML%20Algorithm%20Part%201..png?raw=true"/>  
</p>

## SHAP values per algorithm (model decision explanation based on game theory) 
<img src="https://github.com/amasend/Master-Thesis/blob/master/Figures/Figure%2075.%20Summarize%20the%20Impact%20of%20All%20Features%20Over%20the%20Entire%20Dataset%20Part%201..png?raw=true"/>  

## XGBoost  
5-fold cross validation results per different training dataset size  
<p align="center">
<img src="https://github.com/amasend/Master-Thesis/blob/master/Tables/Table%2022.%205-fold%20Cross-Validation%20XGB%20Metrics%20After%20Grid%20Search..PNG?raw=truee"/>  
</p>
Classification report  
<p align="center">
<img src="https://github.com/amasend/Master-Thesis/blob/master/Tables/Table%2023.%20XGB%20Classification%20Report..PNG?raw=true"/>  
</p>
