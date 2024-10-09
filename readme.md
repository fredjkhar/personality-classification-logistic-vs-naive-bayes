# Empirical Classification Study: Logistic Regression vs. Naive Bayes

## Description
This Jupyter Notebook performs a comparative analysis between Logistic Regression and Naive Bayes classifiers on a multi-class classification problem using the "16 Personalities" dataset. The dataset consists of responses to personality questions and categorizes each individual into one of 16 unique personality types. The main goal is to explore the accuracy and effectiveness of both classifiers using metrics such as precision and recall to gauge their performance.

### Dataset Overview
- **60,000 entries/rows**: Each representing an individual's responses to the personality test.
- **60 features**: Corresponding to test questions designed to capture different aspects of personality.
- **16 unique classes**: Personality types such as `INTJ`, `ENTP`, etc.
- **Target column**: Personality type to be predicted based on responses.

### Algorithms Used
1. **Logistic Regression** (Multi-class)
2. **Categorical Naive Bayes**

The notebook is structured into the following steps:
1. Data Preprocessing and Feature Engineering
2. Model Definitions (Logistic Regression and Naive Bayes)
3. Training and Evaluation for each classifier
4. Hyperparameter Tuning and Further Training
5. Comparison of Results and Analysis

### Prerequisites
Make sure you have the following libraries installed in your environment:

- `pandas`
- `scikit-learn`
- `matplotlib`

### How to Run the Notebook
1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/personality-prediction-notebook.git
    cd personality-prediction-notebook
    ```

2. **Install the Required Packages:**
   If you are using a Jupyter Notebook, run the following commands in a separate code cell to install the dependencies:

   ```python
   !pip install pandas scikit-learn matplotlib