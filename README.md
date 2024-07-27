# Sentiment-Analysis-of-Restaurant-Reviews-EDA-Visualization-and-Comparing-Naive-Bayes-and-SVM-Models
This repository covers the sentiment analysis of restaurant reviews, including Exploratory Data Analysis (EDA), data visualization, and model comparison. It demonstrates the preprocessing steps, the application of Naive Bayes and Support Vector Machines (SVM) models, and evaluates their performance to determine the best approach.
# Sentiment Analysis of Restaurant Reviews: EDA, Visualization, and Comparing Naive Bayes and SVM Models

Welcome to the Sentiment Analysis of Restaurant Reviews project! This repository contains the code and analysis for performing sentiment analysis on restaurant reviews using exploratory data analysis (EDA), visualization techniques, and comparing two machine learning models: Naive Bayes and Support Vector Machines (SVM).

## Project Overview

The goal of this project is to analyze and predict the sentiment (positive or negative) of restaurant reviews. The project involves several key steps:
1. Importing and exploring the dataset.
2. Performing EDA and visualizations.
3. Preprocessing the data.
4. Building and evaluating Naive Bayes and SVM models.
5. Comparing the performance of the models.

## Dataset

The dataset used for this project contains restaurant reviews with their corresponding sentiment labels (liked or not liked).

## Project Structure

- `Sentiment_Analysis.ipynb`: Jupyter notebook containing the code and analysis for the project.
- `Restaurant_Reviews.tsv`: The dataset file in tab-separated format.

## Installation and Usage

1. Clone the repository:
    ```bash
    git clone https://github.com/AryanMithbawkar/Sentiment-Analysis-of-Restaurant-Reviews-EDA-Visualization-and-Comparing-Naive-Bayes-and-SVM-Models.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Sentiment-Analysis-of-Restaurant-Reviews-EDA-Visualization-and-Comparing-Naive-Bayes-and-SVM-Models
    ```
3. Open the Jupyter notebook to explore the analysis and run the code:
    ```bash
    jupyter notebook Sentiment_Analysis.ipynb
    ```

## Key Sections in the Notebook

1. **Importing Dataset**:
    - Loading the dataset and checking its shape.

2. **Basic Exploration**:
    - Displaying the first few rows of the dataset.
    - Descriptive statistics and info of the dataset.

3. **EDA and Visualizations**:
    - Counting positive and negative reviews.
    - Analyzing review lengths.
    - Creating word clouds for all reviews, positive reviews, and negative reviews.
    - Visualizing the distribution of review lengths.

4. **Feature Extraction**:
    - Extracting features using CountVectorizer.

5. **Model Building and Evaluation**:
    - Splitting the dataset into training and testing sets.
    - Training Naive Bayes and SVM models.
    - Evaluating models using confusion matrix, accuracy score, and classification report.

## Conclusion

Based on the evaluation metrics and classification report, the Naive Bayes model performed better than the SVM model for this dataset.

## Results

- **Naive Bayes Model**:
    - Accuracy: 81.3%
    - Precision, Recall, F1-score (details in the notebook).

- **SVM Model**:
    - Accuracy: 77.7%
    - Precision, Recall, F1-score (details in the notebook).

## License

This project is licensed under the MIT License.

## Acknowledgments

Special thanks to [[source of the dataset if applicable]](https://www.kaggle.com/datasets/d4rklucif3r/restaurant-reviews) for providing the dataset.

---

Feel free to explore, use, and contribute to this project! If you have any questions or suggestions, please don't hesitate to reach out.
