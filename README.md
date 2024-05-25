# Multiclass Classification in Python with Class Imbalance Handling

Description:
This repository contains a Jupyter notebook demonstrating multiclass classification in Python using logistic regression, with a focus on addressing class imbalance in the dataset. The notebook showcases resampling techniques applied to an email spam classification dataset and a Myers-Briggs Type Indicator (MBTI) dataset.

**Key Features:**

1. **Dealing with Class Imbalance:** The notebook provides insights into handling class imbalance, a common challenge in classification tasks. It demonstrates techniques to address class imbalance, such as downsampling the majority class and upsampling the minority class.

2. **Resampling the Email Spam Classification Dataset:** The notebook loads a modified version of the Spambase dataset and performs a quick analysis of the distribution of observations across labels. It then applies downsampling and upsampling techniques to balance the dataset before training a logistic regression model.

3. **Logistic Regression on the MBTI Dataset:** The notebook also covers logistic regression training on the MBTI dataset, showcasing the process of vectorizing text data using count vectorization and encoding the target labels using Label Encoder.

4. **Evaluation and Model Comparison:** The notebook evaluates the trained logistic regression model using classification metrics such as precision, recall, and F1-score. It compares the performance of the model trained on the original imbalanced dataset with the model trained on a balanced dataset obtained through resampling techniques.

**Usage:**

Researchers and practitioners interested in multiclass classification tasks, particularly those dealing with imbalanced datasets, can use this repository as a reference. The provided notebook serves as a comprehensive guide, offering insights into data preprocessing, model training, evaluation, and handling class imbalance.

**Dependencies:**

- Python 3.x
- Jupyter Notebook
- NumPy
- pandas
- matplotlib
- seaborn
- scikit-learn
- nltk

**Contributions:**

Contributions to this repository, such as additional resampling techniques, alternative classification algorithms, or enhancements to the evaluation process, are welcome via pull requests.

**License:**

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to use and modify the code for your own projects.
