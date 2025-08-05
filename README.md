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
   - Used grid search and manual experimentation to optimize model parameters.  
   - Best configuration: batch size of 50, and 20 epochs. 
   - This setup resulted in a well-generalized model with strong predictive performance.

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

    The Artificial Neural Network (Categorical Model) achieved the following performance:

    - Accuracy: 87.8%  
    - Precision:  
      - Class 0 (Negative): 0.91  
      - Class 1 (Positive): 0.85  
    - Recall:  
      - Class 0 (Negative): 0.82  
      - Class 1 (Positive): 0.93  
    - F1-Score:  
      - Class 0 (Negative): 0.87  
      - Class 1 (Positive): 0.89  



