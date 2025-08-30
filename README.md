# glass-type-knn-classification.
Glass Type Classification using KNN

This project applies the K-Nearest Neighbors (KNN) algorithm on the Glass Identification dataset to classify different types of glass based on their chemical composition. The goal was to determine the best number of neighbors (K) for optimal performance.

📌 Features

Implemented KNN from Scikit-learn.

Tested multiple values of K (1 to 15).

Plotted Accuracy vs K graph to visualize performance.

Found the best K = 3, which gave the highest accuracy.

🛠️ Technologies Used

Python

Pandas, NumPy

Scikit-learn (KNeighborsClassifier, accuracy_score)

Matplotlib (for graph plotting)

Google Colab

📂 Project Structure
glass-type-knn-classification/
│
├── glass_knn.ipynb   # Jupyter/Colab Notebook
├── README.md          # Documentation

🚀 How to Run

Clone this repository:

git clone https://github.com/your-username/glass-type-knn-classification.git


Open the notebook in Google Colab 
Run all cells to preprocess data, train KNN models, and evaluate results.

📊 Results

Best n_neighbors: 3

📚 Learnings

Importance of hyperparameter tuning (n_neighbors) in KNN.

Distance-based algorithms require scaling for fair results.

Visualizing model accuracy helps in selecting the best parameters.
