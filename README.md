#  Movie Recommender System  

This project implements a **Movie Recommender System** using **Collaborative Filtering**, **Content-Based Filtering**, and a **Hybrid Approach**. It is deployed as a web application using **Flask** and **Ngrok**.

---

##  Features  
 **Collaborative Filtering** using SVD (Singular Value Decomposition) and KNN-based models.  
 **Content-Based Filtering** using TF-IDF vectorization on movie titles.  
 **Hybrid Recommendation System** that combines both approaches for better recommendations.  
 **Flask Web App** where users can enter their User ID to get personalized movie recommendations.  
 **Ngrok Tunnel** for easy local deployment and sharing.  

---

##  Dataset  
The project uses the **MovieLens dataset**, which contains user ratings and movie details. Ensure you have the following files in the working directory:  

- **`ratings.csv`** – Contains user ratings (`userId`, `movieId`, `rating`)  
- **`movies.csv`** – Contains movie metadata (`movieId`, `title`) 
Data set can be downloaded from this link https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset 
  

---

## How It Works
 **Collaborative Filtering**
    Uses SVD and KNN to predict user ratings for unrated movies based on user interactions.
 **Content-Based Filtering**
    Uses TF-IDF to analyze movie titles and compute similarity scores.
 **Hybrid Approach**
    Combines predictions from both methods to provide enhanced recommendations.


---

## Web App UI
 **Home Page** Enter a User ID and request recommendations.
 **Recommendations Page** Displays a list of recommended movies along with predicted ratings.


---

##  Installation & Setup  

### Clone the repository  
```bash
git clone https://github.com/AJ-IITI/Movie-Recommender-System.git
cd Movie-Recommender-System
