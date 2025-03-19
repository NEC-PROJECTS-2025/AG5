"# Computer-Aided Detection of Breast Cancer Using Bio-Inspired Algorithm" 
This project focuses on detecting breast cancer using bio-inspired algorithms for feature selection and classification. By leveraging Genetic Algorithms (GA) for feature selection and optimizing a CNN, the model achieves high accuracy in cancer detection.
Technologies Used

Programming Languages & Frameworks
Python – For model development and implementation.
Flask – Used for backend API development.
HTML, CSS – Frontend design for displaying results.

Development & Execution Environments
Google Colab – Model training and experimentation.
VS Code – Frontend and backend development.

Libraries & Tools
TensorFlow/Keras – Deep learning framework for training the model.
OpenCV – Image processing and feature extraction.
Scikit-learn – Machine learning models and evaluation metrics.
Matplotlib & Seaborn – Data visualization.
Simple Genetic Algorithm (GA) – Feature selection technique.
CNN Classifier – Classification algorithm for cancer detection.

Project Workflow
Data Preprocessing: Images are normalized and enhanced using CLAHE.
ROI Detection: Extracts the region of interest using edge detection.
Feature Extraction: Uses Local Binary Pattern (LBP) for extracting texture features.
Feature Selection: Applies Genetic Algorithm (GA) to select the most relevant features.
Classification: Trains a CNN modelon the selected features.
Evaluation: Computes accuracy, precision, recall, and F1-score.

Results
Achieved 98.88% accuracy using Genetic Algorithm-based feature selection.
Improved feature extraction along with feature selection and classification performance.

Authors
Syed Rizwana
Peddi Kavya
Bolla Vinay Pooja
Bandi Poojitha
