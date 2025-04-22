# Predict-Online-learning-completion

# predict-online-learning-completion_202401100300160
 # 🎓 Online Learning Completion Prediction
 
 This project uses machine learning to predict whether a student will complete an online course based on their activity — such as the number of videos watched, assignments submitted, and forum participation.
 
 ---
 
 ## 📁 Dataset
 
 The dataset is a CSV file named online_learning.csv and contains the following columns:
 
 - videos_watched: Number of course videos watched
 - assignments_submitted: Number of assignments submitted
 - forum_posts: Number of forum posts made
 - completed: Whether the course was completed (yes/no)
 
 ---
 
 ## 🚀 Technologies Used
 
 - *Python*
 - *Pandas* – Data manipulation
 - *NumPy* – Numerical operations
 - *Matplotlib* & *Seaborn* – Data visualization
 - *Scikit-learn* – Machine Learning model and metrics
 
 ---
 
 ## 🧠 Machine Learning Model
 
 We use a *Random Forest Classifier* to classify whether a student will complete the course or not.
 
 ### Process:
 
 1. Load and explore the dataset
 2. Convert the target column completed from yes/no to 1/0
 3. Define input features and target variable
 4. Split the data (80% train, 20% test)
 5. Train the model using a Random Forest Classifier
 6. Predict and evaluate using:
    - Accuracy
    - Classification Report
    - Confusion Matrix
 7. Visualize Feature Importance
 
 ---
 
 ## 📊 Output Example
 
 - *Model Accuracy:* Displayed as a percentage
 - *Classification Report:* Includes precision, recall, F1-score
 - *Confusion Matrix:* Visual representation of predictions
 - *Feature Importance Plot:* Shows which features contribute most to the prediction
 
 ---
 
 ## 💻 How to Run This Project
 
 1. *Clone this repository*  
    ```bash
    git clone https://github.com/your-username/online-learning-prediction.git
    cd online-learning-prediction
