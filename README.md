# RECOMMENDATION-SYSTEM



# 🎬 Movie Recommendation System using Collaborative Filtering & Matrix Factorization

This project showcases a recommendation system built using the **MovieLens 100k** dataset. The system uses both **collaborative filtering** and **matrix factorization** techniques to suggest movies to users based on their historical ratings.

---

## 🚀 Features

- 📦 Based on MovieLens 100k dataset
- 🧠 Collaborative Filtering using User-User Cosine Similarity
- 📉 Matrix Factorization using SVD (Surprise library)
- 📊 Evaluation using RMSE and MAE
- 💡 Sample predictions with confidence score

---

## 📁 Project Structure

📦 recommendation-system ├── Recommendation_System.ipynb # Jupyter Notebook with full code ├── README.md # Project overview and instructions

yaml
Copy
Edit

---

## 🧠 Techniques Used

- **User-User Collaborative Filtering**:
  - Built with cosine similarity between user vectors
- **Matrix Factorization (SVD)**:
  - Implemented using the `surprise` Python library
- **Evaluation**:
  - RMSE and MAE computed via cross-validation

---

## 🧪 Dataset

- **Name:** MovieLens 100k
- **Link:** [GroupLens - MovieLens 100k](https://grouplens.org/datasets/movielens/100k/)
- **Format:** `user_id`, `item_id`, `rating`, `timestamp`
- **Additional Data:** Movie titles and genres

---

## 🛠️ How to Run

1. 📥 Clone the repository or download the notebook:
   ```bash
   git clone https://github.com/your-github/recommendation-system.git
🧪 Install required libraries:

bash
Copy
Edit
pip install pandas numpy scikit-learn scikit-surprise
▶️ Launch the notebook:

bash
Copy
Edit
jupyter notebook Recommendation_System.ipynb

📈 Sample Output
Cross-validation RMSE (SVD): ~0.93

Predicted rating (User 1 on Item 50): 3.8 (out of 5)

