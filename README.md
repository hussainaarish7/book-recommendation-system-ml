# Book Recommendation System using Machine Learning

## Project Overview

This project is a Machine Learning-based Book Recommendation System designed to suggest books to users based on their interests and historical ratings. The system utilizes collaborative filtering techniques and K-Nearest Neighbors (KNN) algorithms to generate personalized book recommendations.

The goal of this project is to improve user experience by helping readers discover books that align with their preferences.

---

## Problem Statement

With thousands of books available online, users often struggle to find relevant books that match their interests. Traditional search methods may not provide personalized recommendations.

This project aims to build an intelligent recommendation system that analyzes user ratings and reading behavior to suggest similar books.

---

## Dataset Information

The project uses the popular Book-Crossing Dataset containing:

### Books Dataset

* 271,360 books
* Book details including title, author, and publisher

### Users Dataset

* 278,858 users
* User demographic information

### Ratings Dataset

* 1,149,780 ratings
* User-book interaction records

---

## Technologies Used

### Programming Language

* Python

### Libraries

* Pandas
* NumPy
* Scikit-Learn
* Pickle

### Machine Learning

* Collaborative Filtering
* Cosine Similarity
* K-Nearest Neighbors (KNN)

### Development Environment

* Jupyter Notebook
* Google Colab

---

## Project Workflow

### 1. Data Collection

* Loaded Books, Users, and Ratings datasets.

### 2. Data Cleaning

* Removed duplicate records.
* Handled missing values.
* Filtered inactive users and low-rated books.

### 3. Exploratory Data Analysis

* Analyzed user behavior.
* Identified popular books.
* Studied rating distributions.

### 4. Feature Engineering

* Created user-book interaction matrix.
* Generated pivot tables for recommendations.

### 5. Model Building

* Implemented K-Nearest Neighbors (KNN).
* Calculated cosine similarity between books.
* Trained recommendation model.

### 6. Model Serialization

* Saved trained models using Pickle files (.pkl).

---

## Files in Repository

### Notebooks

* `book_recommendation_system_using_machine_learning.ipynb`

### Python Application

* `recommendation_system.py`

### Trained Models

* `model_knn.pkl`
* `recommendation_system.pkl`
* `ratings_pivot.pkl`
* `top_books.pkl`
* `top_20_books.pkl`

### Configuration

* `requirements.txt`

---

## Recommendation Techniques Implemented

### Popularity-Based Recommendation

Recommends books that are highly rated and frequently reviewed by users.

### Collaborative Filtering

Suggests books based on similarities between users and books.

### KNN Recommendation Model

Uses nearest-neighbor algorithms to identify books with similar rating patterns.

---

## Key Outcomes

* Developed a personalized recommendation engine.
* Improved book discovery through machine learning.
* Successfully implemented collaborative filtering techniques.
* Generated accurate recommendations based on user preferences.

---

## Future Enhancements

* Deploy using Streamlit.
* Add real-time recommendation capabilities.
* Integrate user authentication.
* Implement hybrid recommendation systems.
* Improve recommendation diversity and accuracy.

---

## Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis (EDA)
* Feature Engineering
* Machine Learning
* Recommendation Systems
* K-Nearest Neighbors (KNN)
* Collaborative Filtering
* Model Deployment Preparation

---

## Author

### Mohd Aarish

Data Analyst | Python | SQL | Power BI | Tableau | Machine Learning

GitHub: https://github.com/hussainaarish7

LinkedIn: https://www.linkedin.com/in/aarish-hussain01/

Email: [hussainaarish7@gmail.com](mailto:hussainaarish7@gmail.com)
