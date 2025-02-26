# Supervised Machine Learning - Classification in Titanic dataset 

## Overview  
This project applies **Supervised Machine Learning** techniques to predict the survival of Titanic passengers based on different features such as **class, age, gender, and fare**. Using Python and libraries like **pandas, scikit-learn, seaborn, and matplotlib**, the dataset is preprocessed, analyzed, and used to train multiple classification models.  

## Dataset  
The project is based on the Titanic dataset from **Kaggle** ([Titanic - Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic/data)).  
- **train.csv** - Training dataset with labels.  
- **test.csv** - Test dataset (without survival labels).  
- **gender_submission.csv** - Sample submission file.  

## Visualizations  
The project includes **data visualizations** such as:  
- **Correlation heatmaps**  
- **Survival rate distributions by gender, class, and age**  
- **Boxplots to analyze age and survival rates**
  
## Key Steps  
- **Data Exploration & Visualization**: Histograms, boxplots, and heatmaps for understanding feature distributions and correlations.  
- **Feature Engineering & Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.  
- **Model Training & Evaluation**: Implementing **Logistic Regression, Random Forest, SVM, Gradient Boosting, and K-Nearest Neighbors**, and evaluating their performance using **accuracy, precision, recall, and confusion matrices**.  
- **Model Selection & Prediction**: Choosing the best model and making final predictions for the test dataset.  

## 📈 Results  
The models are evaluated based on accuracy and classification reports. The best-performing model is selected for generating predictions.  

### Sample Model Performance  
| Model                  | Accuracy |  
|------------------------|----------|  
| Logistic Regression    | 80.45%   |  
| Random Forest         | 82.12%   |  
| Support Vector Machine | 81.01%   |  
| Gradient Boosting     | 80.45%   |  
| K-Nearest Neighbors   | 78.77%   |  

## License  
This project is licensed under the **MIT License**. Feel free to use, modify, and share it.  

## Contributing  
Contributions are welcome! If you find any issues or improvements, feel free to open an **issue** or submit a **pull request**.  

