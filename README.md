# Income Prediction using Machine Learning

This repository contains a machine learning project aimed at predicting whether an individual's annual income exceeds $50,000 based on their demographic and personal information. The project utilizes the Adult Income Dataset, which is widely cited in machine learning literature and is sourced from the UCI Machine Learning Repository.

![output 2](https://github.com/user-attachments/assets/d2961da3-49e4-4e3a-935b-0f765662300a)
![output](https://github.com/user-attachments/assets/2b7b29b7-d800-48dc-8dd2-54cf573e9ca6)

## Project Overview

The goal of this project is to build a predictive model that can accurately classify whether an individual's income is greater than $50,000 (`>50K`) or less than or equal to $50,000 (`<=50K`). The dataset includes various attributes that describe an individual's demographics and other relevant features, such as age, education level, occupation, and more.

### Dataset

- **Source**: UCI Machine Learning Repository
- **Reference Dataset URL**: [Adult Income Dataset on Kaggle](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset)
- **Original Dataset URL**: [Adult Dataset on UCI](https://www.cs.toronto.edu/~delve/data/adult/adultDetail.html)
- **Number of Instances**: 48,842 (32,561 for training, 16,281 for testing)
- **Number of Attributes**: 14 features + 1 target variable (Income)
- **Attributes**:
  1. `age`: Continuous
  2. `workclass`: Categorical (e.g., Private, Self-emp, Government)
  3. `fnlwgt`: Continuous
  4. `education`: Categorical (e.g., Bachelors, Masters, Doctorate)
  5. `education-num`: Continuous
  6. `marital-status`: Categorical (e.g., Married, Never-married, Divorced)
  7. `occupation`: Categorical (e.g., Tech-support, Sales, Exec-managerial)
  8. `relationship`: Categorical (e.g., Wife, Own-child, Husband)
  9. `race`: Categorical (e.g., White, Black, Asian-Pac-Islander)
  10. `sex`: Categorical (e.g., Female, Male)
  11. `capital-gain`: Continuous
  12. `capital-loss`: Continuous
  13. `hours-per-week`: Continuous
  14. `native-country`: Categorical (e.g., United-States, Canada, Mexico)
  15. `income`: Categorical (Target variable: `<=50K`, `>50K`)

### Objective

The primary objective of this project is to explore and analyze the dataset to uncover the relationships between different features and the target variable (Income). Based on the analysis, various machine learning algorithms will be applied to build a model that can predict the income class of an individual.

### Steps Involved

1. **Data Preprocessing**: Handling missing values, encoding categorical features, and normalizing numerical features.
2. **Exploratory Data Analysis (EDA)**: Understanding the distribution of features and their relationships with the target variable.
3. **Model Building**: Applying different machine learning algorithms like Logistic Regression, Decision Trees, Random Forest, and more.
4. **Model Evaluation**: Assessing the performance of the models using metrics such as accuracy, precision, recall, F1-score, and ROC-AUC.

### Results
- Obtained a model Score: of 84.58% without hyperparameter tuning.
- Obtained a random forest score of 86.40% After hyperparameter tuning of the model.

## Acknowledgements

This dataset was originally extracted from the 1994 U.S. Census by Barry Becker and has been a popular choice for benchmarking machine learning algorithms. The dataset is publicly available on the UCI Machine Learning Repository.

## References

- [UCI Machine Learning Repository - Adult Dataset](https://www.cs.toronto.edu/~delve/data/adult/adultDetail.html)
- Ron Kohavi, "Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid", Proceedings of the Second International Conference on Knowledge Discovery and Data Mining, 1996.

## How to Use

1. Clone this repository to your local machine.
## Getting Started


    ```
    git clone https://github.com/gappeah//Income-Prediction-ML.git
    ```
## File Structure

```
root
│
├── README.md
├── main.ipynb
└── adult.csv
```

2. Install the necessary dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter notebooks provided to explore the dataset, build models, and evaluate their performance.
4. Experiment with different algorithms and hyperparameters to improve the model's accuracy.

## Contributing

Contributions to this project are welcome. If you have any improvements or additional models to suggest, please create a pull request or open an issue for discussion.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
