# 🎬 Movie Recommendation Engine

A machine learning-based recommendation system that generates personalized movie suggestions using collaborative filtering and content-based filtering techniques.

---

## 📌 Project Overview

This project builds an end-to-end recommendation engine that analyzes user-movie interaction data to predict and surface movies a user is most likely to enjoy. It combines two filtering strategies to improve accuracy and handle both new and returning users effectively.

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Pandas | Data loading, cleaning, and transformation |
| NumPy | Numerical operations |
| Scikit-learn | Similarity computation and ML utilities |
| Jupyter Notebook | Development and experimentation environment |

---

## ✨ Features

- **Collaborative Filtering** – Recommends movies based on similar users' preferences
- **Content-Based Filtering** – Recommends movies based on movie attributes and user history
- **Hybrid Approach** – Combines both methods to reduce cold-start issues for new users
- **Similarity Scoring** – Uses cosine similarity to rank and surface top-N recommendations
- **Personalized Output** – Generates unique recommendation lists per user

---

## 📁 Project Structure

```
Movie-Recommendation/
│
├── data/                  # Dataset files (user-movie interactions)
├── Movie_Recommendation.ipynb  # Main notebook with full pipeline
├── requirements.txt       # Python dependencies
└── README.md
```

---

## 🚀 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/vikramdev277-netizen/Movie-Recommendation.git
   cd Movie-Recommendation
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Open the notebook**
   ```bash
   jupyter notebook Movie_Recommendation.ipynb
   ```

4. Run all cells to train the model and generate recommendations.

---

## 📊 Results

- Analyzed 10,000+ user-movie interaction records
- Generated personalized Top-N movie recommendations per user
- Improved recommendation relevance by combining two filtering strategies

---

## 👤 Author

**Vikram Dev Bhadoriya**  
B.Tech – Computer Science & Engineering, Amity University Madhya Pradesh  
📧 Vikramdev277@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/vikram-devbhadauriya-a16692329)

