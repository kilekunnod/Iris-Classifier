## Iris Classification Model 🌸  

This project is a **machine learning model** that classifies iris flowers into three species: **Setosa, Versicolor, and Virginica** using the **Iris dataset**.  

### 📌 Features  
- Loads and explores the **Iris dataset** from `scikit-learn`  
- Uses a **k-Nearest Neighbors (k-NN) classifier** to predict flower species  
- Splits data into **training and testing sets**  
- Evaluates model performance using accuracy metrics  

### 🔧 Installation  
1. Clone the repository  
   ```bash
   git clone https://github.com/kilekunnod/Iris-Classification.git
   cd Iris-Classification
   ```
2. Create and activate a virtual environment (recommended)  
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # macOS/Linux  
   .venv\Scripts\activate     # Windows  
   ```
3. Install dependencies  
   ```bash
   pip install -r requirements.txt
   ```


### 📊 Dataset  
The dataset contains **150 samples**, each with **4 features**:  
- Sepal length  
- Sepal width  
- Petal length  
- Petal width  

Target classes: **Setosa (0), Versicolor (1), Virginica (2)**  

### 🛠️ Dependencies  
- Python 3.10+  
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-learn  
