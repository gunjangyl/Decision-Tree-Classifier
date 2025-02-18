# Decision-Tree-Classifier

# Decision Tree Classifier for Iris Dataset 🌿🌸  

## Overview  
This project implements a **Decision Tree Classifier** to classify **Iris flower species** using the **Iris dataset**. The decision tree algorithm is a powerful and interpretable machine learning model that splits data based on feature conditions to make predictions.  

---

## Dataset 📊  
The **Iris dataset** consists of **150 samples**, each with **four features**:  
- **Sepal Length (cm)**  
- **Sepal Width (cm)**  
- **Petal Length (cm)**  
- **Petal Width (cm)**  

Each sample belongs to one of **three classes**:  
- **Iris Setosa (0)** 🌿  
- **Iris Versicolor (1)** 🌺  
- **Iris Virginica (2)** 🌸  

---

## Project Workflow 🚀  
1. **Load the Dataset** using `sklearn.datasets`.  
2. **Data Preprocessing**: Split into training & testing sets.  
3. **Train a Decision Tree Classifier** using `sklearn.tree.DecisionTreeClassifier`.  
4. **Evaluate the Model** using accuracy score and confusion matrix.  
5. **Visualize the Decision Tree** using `graphviz`.  

---

## Installation & Usage 🔧  
### 1️⃣ Clone the Repository  
git clone https://github.com/your-username/DecisionTree-Iris.git
cd DecisionTree-Iris

2️⃣ Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt

3️⃣ Run the Script
bash
Copy
Edit
python decision_tree_iris.py

Results & Observations 📈
The Decision Tree classifier achieves high accuracy on the test dataset.
The tree structure helps in understanding feature importance.
Example Confusion Matrix:

lua
Copy
Edit
[[50  0  0]  
 [ 0 48  2]  
 [ 0  1 49]]
 
📌 Contributing
Contributions are welcome! Feel free to fork the repo and improve the model.

