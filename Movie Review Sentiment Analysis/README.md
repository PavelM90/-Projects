# Movie Sentiment Analysis using NLP and Classification Models
![Image_Movie](images/example-image-movie.png)


This Jupyter Notebook demonstrates a movie sentiment analysis using Natural Language Processing (NLP) techniques and various classification models. The project aims to analyze and predict the sentiment (positive or negative) expressed in movie reviews.

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Libraries and Tools](#libraries-and-tools)
4. [Workflow](#workflow)
5. [Models Used](#models-used)
6. [Results](#results)
7. [How to Run](#how-to-run)
8. [Contributing](#contributing)
9. [License](#license)

## Overview

Sentiment analysis is a key application of NLP in determining the sentiment behind text data. This notebook analyzes movie reviews to classify their sentiment using various machine learning models. The goal is to explore different models, compare their performance, and understand which model works best for this particular task.

## Dataset

The dataset used in this project consists of movie reviews and their corresponding sentiment labels (positive/negative). This dataset can be publicly available, like IMDb or a custom one.
Link to the data set
https://ai.stanford.edu/~amaas/data/sentiment/
## Libraries and Tools

The following libraries and tools are used in this notebook:

- **NLTK**: For text preprocessing and NLP tasks.
- **scikit-learn**: For model building, evaluation, and metrics.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib/Seaborn**: For data visualization.
- **Jupyter Notebook**: For an interactive coding environment.


- **Pandas version: 2.2.2**
- **PNLTK version: 3.8.1**
- **PNumpy version: 1.26.4**
- **Pscikit-learn version: 1.4.2**
- **PMatplotlib version: 3.8.4**
- **PSeaborn version: 0.13.2**
  
## Workflow

The workflow of the notebook includes:

1. **Data Loading**: Importing the dataset into the notebook.
2. **Data Preprocessing**: Cleaning and preparing the text data (e.g., tokenization, removing stopwords).
3. **Feature Extraction**: Converting text data into numerical features using techniques like TF-IDF.
4. **Model Training**: Training various classification models on the processed data.
5. **Model Evaluation**: Evaluating the models using appropriate metrics (e.g., accuracy, F1-score).
6. **Comparison of Models**: Comparing the performance of different models to determine the best one.
7. **Conclusion**: Summarizing the findings and suggesting potential improvements.

## Models Used

The notebook explores the following models:

- **Logistic Regression**
- **Support Vector Machine (SVM)**


## Results

The notebook compares the performance of the models based on metrics like accuracy, precision, recall, and F1-score. The results section includes visualizations and tables to help understand the effectiveness of each model.
The trained Logistic Regression model demonstrated better performance than the trained SVM model based on the precision, recall, and F1 metrics.

## Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements or fixes.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
