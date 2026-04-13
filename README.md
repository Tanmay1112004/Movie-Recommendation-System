# 🎬 Movie Recommendation System — AI That Understands Your Taste

<p align="center">
  <b>Discover movies based on content, not popularity</b><br>
  Built with Machine Learning, NLP & real-time API integration
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8+-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/ML-Scikit--learn-orange?style=flat-square"/>
  <img src="https://img.shields.io/badge/UI-Streamlit-red?style=flat-square"/>
  <img src="https://img.shields.io/badge/API-TMDB-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Status-Production%20Ready-brightgreen?style=flat-square"/>
</p>

---

## 💡 What This Project Actually Does

Most recommendation systems rely on **ratings or user history**.

👉 This one doesn’t.

Instead, it understands **what a movie *is*** — and recommends similar ones instantly.

**Input:** Movie name
**Output:** Top 10 similar movies + posters + details

---

## 🚨 Problem Statement

Streaming platforms have thousands of movies.

👉 Users waste more time *choosing* than *watching*.

Traditional recommenders:

* Depend on user data (cold-start issue)
* Bias toward popular content

---

## 🎯 Solution

A **content-based recommendation engine** that:

✅ Works without user history
✅ Recommends niche & underrated movies
✅ Provides explainable results
✅ Delivers fast, real-time suggestions

---

## ⚡ Key Features

### 🎯 Intelligent Recommendations

* Content-based filtering using ML
* Top-10 similar movies in milliseconds

### 🧠 NLP-Powered Understanding

* Uses movie metadata (genre, cast, overview)
* Converts text → vectors → similarity scores

### 🖼️ Real-Time Posters

* Fetches posters via TMDB API
* Enhances user experience visually

### 💻 Interactive UI

* Built with Streamlit
* Simple, fast, and user-friendly

---

## 🧠 Why This Project Stands Out (Recruiter POV)

Most ML projects = Jupyter notebooks.

This one 👇

✅ End-to-end ML system
✅ NLP + recommendation engine
✅ API integration (real-world data)
✅ Clean deployable UI
✅ Product-level thinking

👉 Translation: *You build usable systems, not just models.*

---

## 🧬 How It Works

### Core Idea:

Movies with similar **content features** → similar recommendations

---

### 🔬 Pipeline

1. **Data Preprocessing**

   * Merge genres, keywords, cast, overview
   * Clean & normalize text

2. **Feature Engineering**

   * Convert text → vectors (BoW / TF-IDF)

3. **Similarity Computation**

   * Cosine similarity between movie vectors

4. **Recommendation Engine**

   * Retrieve Top-N closest matches

5. **API Integration**

   * Fetch posters from TMDB

---

## 🏗️ System Architecture

```
User Input (Movie Title)
        │
        ▼
Content Processing
        │
        ▼
Vectorization (TF-IDF / BoW)
        │
        ▼
Cosine Similarity Engine
        │
        ▼
Top 10 Movies
        │
        ▼
TMDB API (Posters)
        │
        ▼
Streamlit UI
```

---

## 🛠 Tech Stack

| Layer           | Technology    |
| --------------- | ------------- |
| Programming     | Python        |
| ML / NLP        | Scikit-learn  |
| Data Processing | Pandas, NumPy |
| Frontend        | Streamlit     |
| API             | TMDB API      |

---

## 🚀 Quick Start

```bash id="start123"
# Clone repo
git clone https://github.com/Tanmay1112004/Movie-Recommendation-System.git

# Install dependencies
pip install -r requirements.txt

# Run app
streamlit run app.py
```

👉 Open: `http://localhost:8501`

---

## 📂 Project Structure

```id="struct22"
Movie-Recommendation-System/
│
├── app.py
├── model.pkl
├── movies.pkl
├── requirements.txt
├── README.md
└── screenshots/
```

---

## 📊 Why Content-Based Recommendation?

| Advantage             | Impact            |
| --------------------- | ----------------- |
| No cold-start problem | Works instantly   |
| Explainable results   | Transparent logic |
| Niche discovery       | Finds hidden gems |
| No user data needed   | Privacy-friendly  |

---

## 🎓 What This Project Demonstrates

* Machine Learning fundamentals
* Natural Language Processing (NLP)
* Feature engineering & similarity modeling
* API integration
* Full-stack ML deployment
* Product thinking

---

## 🔮 Future Enhancements

* [ ] Hybrid recommendation system
* [ ] User personalization
* [ ] Deep learning embeddings
* [ ] Movie trailers integration
* [ ] Mobile responsive UI

---

## 🤝 Contributing

```bash id="contri22"
git checkout -b feature/amazing-feature
git commit -m "Add feature"
git push origin feature/amazing-feature
```

---

## 👨‍💻 About the Developer

**Tanmay Kshirsagar**
Final Year Computer Engineering Student

Building at the intersection of:
👉 AI • Data • Products • Full-Stack Development

---

## ⭐ Support

If this project impressed you:

* ⭐ Star the repo
* 🍴 Fork it
* 🚀 Share it

---

## 🔥 Final Thought

Most recommenders follow the crowd.

👉 This one helps you discover what you’d *actually enjoy.*

---

<p align="center">
  🎬 <b>Stop scrolling. Start discovering.</b>
</p>
