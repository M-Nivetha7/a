# 🌌 Galaxy Morphology Classification

This project classifies galaxies based on their shapes and structures using machine learning. The goal is to explore galaxy images and automatically categorize them into morphological types.

## 🧪 Project Overview

Galaxy morphology classification helps astronomers understand galaxy formation and evolution. This project uses image data to classify galaxies as spiral, elliptical, or irregular using ML techniques.

## 📂 Repository Structure
```
├── Galaxy_Morphology_Classification.ipynb  # Main notebook with all code, data exploration, preprocessing, model training, and evaluation
├── .gitattributes                          # Git configuration
└── README.md                                # Project description and instructions
```
## 🔧 Algorithms & Methods Used

### 1. Data Preprocessing
- Image resizing and normalization
- Handling missing or corrupted data

### 2. Exploratory Data Analysis (EDA)
- Visualizing galaxy types
- Checking class distribution

### 3. Machine Learning Models
- **Random Forest Classifier** - Ensemble learning method using multiple decision trees
- **Support Vector Machines (SVM)** - Finds optimal hyperplane for classification
- **K-Nearest Neighbors (KNN)** - Classifies based on similarity to nearby data points

### 4. Evaluation Metrics
- Accuracy, Precision, Recall, F1-score
- Confusion matrix visualization

## ⚡ Workflow

1. Load galaxy image dataset
2. Preprocess images (resize, normalize)
3. Perform EDA to understand class distribution
4. Split data into training and testing sets
5. Train multiple ML classifiers
6. Evaluate model performance
7. Visualize predictions and performance metrics

## 🚀 How to Run

### Step 1: Clone the repository
```
git clone https://github.com/M-Nivetha7/Space_Research_3.git
```

### Step 2: Navigate to the project folder
```
cd Space_Research_3
```

### Step 3: Install dependencies
```
pip install numpy pandas matplotlib scikit-learn opencv-python jupyter
```

### Step 4: Open the Jupyter Notebook
```
jupyter notebook Galaxy_Morphology_Classification.ipynb
```



## 💻 Code Example

# Example: Training Random Forest Classifier
```
from sklearn.ensemble import RandomForestClassifier
from sklearn.metrics import accuracy_score, classification_report
```

# Initialize and train the model
```
rf_model = RandomForestClassifier(n_estimators=100, random_state=42)
rf_model.fit(X_train, y_train)
```

# Make predictions
```
y_pred = rf_model.predict(X_test)
```

# Evaluate
```
accuracy = accuracy_score(y_test, y_pred)
print(f"Accuracy: {accuracy:.2f}")
print(classification_report(y_test, y_pred))
```

## 📦 Dependencies

```
numpy>=1.21.0
pandas>=1.3.0
matplotlib>=3.4.0
scikit-learn>=0.24.0
opencv-python>=4.5.0
jupyter>=1.0.0
```

## 👩‍💻 Author

**M. Nivetha**  
B.Tech Artificial Intelligence and Machine Learning  
R.M.D Engineering College

## 📌 Important Notes

### Repository Name Update
This repository was previously named `a` and has been updated to `Space_Research_3`. 

If you have cloned the old version, update your remote URL using:
git remote set-url origin https://github.com/M-Nivetha7/Space_Research_3.git

### Dataset Information
- The galaxy images used in this project are from [add dataset source here]
- Images are preprocessed to uniform size before training
- Classes: Spiral, Elliptical, and Irregular galaxies

## 🔮 Future Improvements

- [ ] Implement deep learning models (CNN, Transfer Learning)
- [ ] Add more galaxy subclasses (e.g., barred spirals)
- [ ] Create a web app for real-time classification
- [ ] Deploy model using Flask/FastAPI
- [ ] Add data augmentation for better accuracy

## 📚 References

- [Add any research papers or resources you used]
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Galaxy Zoo Project](https://www.zooniverse.org/projects/zookeeper/galaxy-zoo/)
  

## ⭐ Show your support

If you found this project helpful, please give it a ⭐ on GitHub!

---

**Happy Coding!** 🚀
