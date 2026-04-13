🌸 Iris Flower Classification using PyTorch

📌 Project Overview

This project demonstrates a complete Machine Learning pipeline for classifying iris flowers into three species using a Neural Network built with PyTorch.

The dataset used is the classic Iris Dataset, which contains measurements of flower features such as petal and sepal dimensions. The goal is to predict the correct flower species based on these measurements.



⸻

🎯 Objectives
	•	Perform Exploratory Data Analysis (EDA)
	•	Visualize relationships between features
	•	Preprocess and scale data
	•	Build a Neural Network using PyTorch
	•	Train the model using CrossEntropyLoss
	•	Evaluate performance using Accuracy, Confusion Matrix, and Classification Report

  
⸻

📊 Dataset Information

Dataset: Iris Dataset
Source: sklearn.datasets

Number of Samples: 150
Number of Features: 4
Number of Classes: 3

Features:
	•	Sepal Length
	•	Sepal Width
	•	Petal Length
	•	Petal Width

Target Classes:
	•	0 → Setosa
	•	1 → Versicolor
	•	2 → Virginica

⸻
🔍 Exploratory Data Analysis (EDA)

The following steps were performed during EDA:
	•	Display dataset preview using head()
	•	Check dataset shape
	•	Inspect data types using info()
	•	Generate statistical summary using describe()
	•	Check for missing values
	•	Analyze class distribution
	•	Create pairplots
	•	Generate histograms
	•	Plot correlation heatmap

Key Observations
	•	No missing values detected
	•	Dataset is balanced (50 samples per class)
	•	Strong correlation between petal length and petal width
	•	Setosa class is clearly separable

⸻
⚙️ Data Preprocessing

Steps included:
	•	Split dataset into training and testing sets
	•	Feature scaling using StandardScaler
	•	Convert data into PyTorch tensors

Train/Test Split:
	•	Training Data: 80%
	•	Testing Data: 20%

⸻
🧠 Model Architecture

Neural Network Structure:
	•	Input Layer: 4 features
	•	Hidden Layer: 16 neurons (ReLU activation)
	•	Output Layer: 3 neurons (3 classes)

Loss Function:

CrossEntropyLoss

Optimizer:

Adam Optimizer
Learning Rate: 0.01

⸻
🔁 Training Process

The model was trained for 100 epochs.

Training workflow:
	1.	Forward pass
	2.	Loss calculation
	3.	Backpropagation
	4.	Weight update

The training loss decreased consistently, indicating successful learning.

⸻
📈 Model Evaluation

Evaluation metrics used:
	•	Accuracy
	•	Confusion Matrix
	•	Classification Report

Final Results

Accuracy: 100%

Confusion Matrix:

All predictions were correctly classified.

Classification Report:

Precision: 1.00
Recall: 1.00
F1-score: 1.00

This indicates perfect classification performance on the test dataset.

⸻
🧰 Technologies Used
	•	Python
	•	PyTorch
	•	NumPy
	•	Pandas
	•	Matplotlib
	•	Seaborn
	•	Scikit-learn

⸻
📂 Project Structure

Iris_Classification_Project/

├── Iris_Classification.ipynb
├── README.md
└── requirements.txt

⸻
🚀 Future Improvements
	•	Experiment with deeper neural networks
	•	Perform hyperparameter tuning
	•	Compare results with other ML algorithms
	•	Apply the workflow to larger datasets

⸻

⸻

👩‍💻 Author

Machine Learning project built using PyTorch as part of a classification learning journey.

⸻
