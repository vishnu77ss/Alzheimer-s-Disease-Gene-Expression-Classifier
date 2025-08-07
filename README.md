🧠 Alzheimer's Disease Gene Expression Classifier
This project uses gene expression data to classify whether a sample belongs to a Control group or an Alzheimer's Disease (AD) group using machine learning techniques. The dataset is processed, analyzed using PCA, and classified using a Random Forest Classifier.

📁 Dataset
File Name: GSE278723_AD_C.csv

Description: Contains gene expression data of multiple samples labeled as either Control (_C) or Alzheimer's Disease (_AD).

🧪 Technologies Used
Python

Pandas & NumPy

Matplotlib & Seaborn

Scikit-learn

SciPy

🧬 Workflow Summary
Data Preparation: Load and parse gene expression data. Extract condition labels (Control vs. Alzheimer's).

Preprocessing: Transpose data so that samples are rows. Standardize features using StandardScaler.

Dimensionality Reduction: Apply Principal Component Analysis (PCA) to reduce dimensionality while retaining significant variance.

Classification: Split the dataset into training and testing sets. Train a Random Forest Classifier and evaluate its performance.

Visualization: Plot the explained variance from the PCA to understand the impact of each principal component.

📊 Output Metrics
Accuracy Score

Precision, Recall, F1-score (from Classification Report)

ROC AUC Score

📈 Example Visualization
PCA Explained Variance Plot: A plot showing the amount of variance captured by each principal component.

🛠️ How to Run
Clone this repository.

Place the dataset file GSE278723_AD_C.csv in the project folder.

Run the script from your terminal: python your_script_name.py

📌 Note: Ensure all required libraries are installed by running:
pip install pandas numpy matplotlib seaborn scikit-learn scipy

🧑‍💻 Author

Vishnu Murthy - Web Developer & ML Enthusiast

[\href{https://www.linkedin.com/in/vishnu-murthy-mediboina/}{LinkedIn}] | [\href{https://github.com/vishnu77ss}{GitHub}]
