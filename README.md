# CATTLEID
Individual Cattle Identification using Face Images

# About the Program

This project presents a Python-based algorithm for identifying individual cattle using face images. The cattle face images were collected from an organized farm and stored in directories labeled with their respective cattle IDs.
The dataset is divided into training and testing sets. For each cattle, a separate folder is created inside the training directory. Images of the same cattle used for testing are stored in the test directory.
The Histogram of Oriented Gradients (HOG) feature extraction technique is applied to each image to capture important facial characteristics. Three machine learning algorithms are then used for classification:

- **•	K-Nearest Neighbor (KNN)**
- **•	Support Vector Machine (SVM)**
- **•	Decision Tree**

The trained models are applied to the test image set, and the prediction results of each algorithm are saved in an Excel file.
Problem Statement
The goal of this project is to automatically identify individual cattle using their facial images. The system extracts HOG features from cattle face images and classifies them using machine learning algorithms such as KNN, SVM, and Decision Tree.

# Programming Language and Algorithms Used
Programming Language
- **•	Python**
Machine Learning Algorithms
- **•	K-Nearest Neighbor (KNN)**
- **•	Support Vector Machine (SVM)**
- **• Decision Tree**
  
# Technological Workflow
1.	Load training images
2.	Extract HOG features from each image
3.	Train the KNN classifier
4.	Perform cross-validation
5.	Predict the class of testing images
6.	Save the prediction results to an Excel file

# How to Run the Program
1.	Clone the repository from GitHub
Open command prompt or terminal
•	git clone satyenkgec/CATTLEID: Face Image based cattle Identification
2.	Navigate the repository directory
Change your working directory to clone repository
3.	Open Jupyter Notebook
4.	Access the Notebook
In Jupyter Notebook, navigate to the cloned repository folder
Open the .ipynb Notebook files you want to run
5.	Run the Python code
.







