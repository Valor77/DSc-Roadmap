## 🌊 Groundwater Quality Classification using Machine Learning

This project applies machine learning techniques to classify groundwater quality into categories (Excellent, Good, Fair, Poor) based on physicochemical parameters such as **pH, dissolved oxygen, salinity, turbidity, and more**.  

### 🔎 Objective
The goal is to evaluate and compare the performance of multiple machine learning models in predicting water quality, using the **CCME-WQI (Canadian Water Quality Index)** framework to derive the target labels.  

### 🛠️ Models Evaluated
- Decision Tree  
- Random Forest  
- XGBoost  
- AdaBoost  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Artificial Neural Network (MLPClassifier)  

### 📊 Results
- **Decision Tree (Accuracy: 0.99)** and **ANN (Accuracy: 0.99)** achieved the highest performance, though the tree may risk overfitting.  
- **Random Forest (0.97)** and **XGBoost (0.97)** delivered stable, well-balanced results.  
- **SVM (0.96)** and **KNN (0.96)** performed decently but with slightly lower recall/precision balance.  

### ✅ Key Takeaways
- Ensemble methods and neural networks provide the most reliable performance.  
- The project demonstrates how different models behave on environmental datasets and provides insights into the trade-offs between **accuracy, precision, recall, and generalization**.  

### 📂 Applications
- Groundwater monitoring and management  
- Environmental impact assessments  
- Decision support for policymakers in water resource management  
