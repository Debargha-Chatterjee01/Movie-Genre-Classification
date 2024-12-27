# Movie Genre Classification  

This project aims to build a machine learning model that predicts the genre of a movie based on its plot summary. The dataset, available on [Kaggle](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb), contains movie plot summaries and corresponding genre labels.

## Project Overview  

1. **Data Preprocessing:**  
   The text data is preprocessed by cleaning the plot summaries and converting them into numerical features using **TF-IDF**.

2. **Modeling:**  
   Classification algorithms such as **Logistic Regression**, **Naive Bayes**, and **Support Vector Machines (SVM)** are trained to predict movie genres.

3. **Evaluation:**  
   Model performance is evaluated using metrics such as **accuracy**, **precision**, **recall**, and **F1-score** to determine the effectiveness of each classifier.

4. **Insights and Conclusion:**  
   The models performed reasonably well, with Logistic Regression and SVM achieving the highest accuracy (around 58%). Further improvements can be made by exploring hyperparameter tuning and addressing class imbalance.

## Technologies Used  

- **Python**  
- **Libraries:** scikit-learn, pandas, matplotlib, seaborn  
- **Data Source:** [Kaggle Genre Classification Dataset](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb)  

## Files in the Repository  

- **`movie_genre_classification.ipynb`**: Contains the complete project workflow, from data preprocessing to model evaluation.
