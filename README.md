# cricket-match-prediction
This project predicts cricket match winners based on historical data using Machine Learning algorithms. The dataset includes past matches with key features like teams, venue, toss decisions, and performance statistics


# 🏏 Cricket Match Prediction Using Machine Learning (KNN)

## 📌 Project Overview  
This project predicts **cricket match winners** using the **K-Nearest Neighbors (KNN) algorithm** based on historical match data between **India and Australia**.  
It leverages **team statistics, toss decisions, and match locations** to classify the likely winner.

---

## **📊 Technologies Used**  
- **Python** (Pandas, NumPy, Scikit-Learn)  
- **Machine Learning (K-Nearest Neighbors - KNN)**  
- **Data Preprocessing (Label Encoding, Feature Engineering)**  
- **Google Colab for Model Training & Testing**  
- **GitHub for Project Hosting**  

---

## **🔍 How It Works**  
1️⃣ **Loads historical match data** from `all_champions_trophy_matches_results.csv`.  
2️⃣ **Filters matches between India & Australia** for analysis.  
3️⃣ **Encodes categorical values** (`Team1`, `Team2`, `Toss`, `Ground`, `Winner`) into numerical form using `LabelEncoder()`.  
4️⃣ **Trains a KNN model** to predict match winners.  
5️⃣ **Evaluates accuracy** using `train_test_split()` & `accuracy_score()`.  
6️⃣ **Predicts the outcome of a new match** based on team & toss conditions.  

---

## **📂 Files in This Repository**  
- `cricket_prediction.ipynb` → **Google Colab Notebook** with full code.  
- `all_champions_trophy_matches_results.csv` → **Dataset** of past matches.  
- `README.md` → **Project documentation (this file).**  

---

## **🚀 How to Run This Project**  
1️⃣ **Clone the repository**:  
   ```bash
   git clone https://github.com/yourusername/cricket-match-prediction.git
