# Heart Attack Prediction using Deep Learning

This project uses Artificial Neural Networks (ANN) to predict the risk of heart attacks based on structured medical data. The model is optimized through hyperparameter tuning and evaluated using standard classification metrics to support early diagnosis and medical decisions.

### Project Objective

Build a neural network model to predict heart disease risk using medical features. The workflow includes data preprocessing, hyperparameter tuning, model training, and evaluation using classification metrics.

### Methods Used

- Artificial Neural Network (ANN)  
- Binary Classification  
- Data Preprocessing  
- Feature Correlation Analysis  
- Hyperparameter Tuning  

### Language

- Python

### Libraries and Modules

- pandas  
- numpy  
- matplotlib  
- seaborn  
- scikit-learn  
- tensorflow / keras  

### Step-by-Step

1. **Data Collection**  
   Imported the dataset and required Python libraries.

2. **Initial Data Analysis**  
   Explored data structure, feature distribution, and basic statistics.

3. **Cleaning Data**  
   - Removed missing values and duplicates to maintain data quality.  
   - Ensured all medical features were in numerical format.  
   - Clean data improved model stability and performance.

4. **Encoding Data**  
   Converted categorical features (if any) into numerical representations.

5. **Tuning Hyperparameters**  
   - Conducted grid search to find optimal model configuration.  
   - Best configuration: 3 hidden layers with 300 neurons each.  
   - Resulted in high model performance without signs of overfitting.

6. **Splitting and Normalizing Data**  
   Divided dataset into training and test sets and applied feature scaling.

7. **Data Visualization**  
   Used plots such as histograms and heatmaps to analyze feature importance and distribution.

8. **Multicollinearity Test**  
   Identified highly correlated features to reduce redundancy.

9. **Model Building**  
   Built and trained the ANN using TensorFlow/Keras.

10. **Model Evaluation**  
    Evaluated model performance using accuracy, precision, recall, F1-score, and confusion matrix.

    The Artificial Neural Network achieved the following performance:

    - Accuracy: 92.7%  
    - Precision:  
      - Positive class: 0.94  
      - Negative class: 0.91  
    - Recall:  
      - Positive class: 0.92  
      - Negative class: 0.93  
    - F1-Score:  
      - Positive class: 0.93  
      - Negative class: 0.92  



### Folder Structure

