# 🎬 Movie Recommendation System

A **Content-Based Movie Recommendation System** built using **Python** and **Machine Learning** that suggests movies similar to a given input based on their features like genres, keywords, and overview.

---

## 📌 Project Overview

This project uses **Natural Language Processing (NLP)** techniques and **cosine similarity** to recommend movies. It analyzes movie metadata and finds similarities between movies to generate accurate recommendations.

---

## 🚀 Features

* 🎥 Recommend movies based on user input
* 🔍 Content-based filtering using movie features
* 🧠 TF-IDF vectorization for text processing
* 📊 Cosine similarity for finding similar movies
* 💬 Interactive command-line interface
* 🔁 Continuous user input until exit

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLP (TF-IDF Vectorizer)

---

## 📂 Dataset

* TMDB 5000 Movies Dataset
* Contains:

  * Movie titles
  * Genres
  * Keywords
  * Overview

👉 You can download it from Kaggle.

---

## ⚙️ How It Works

1. Load the dataset
2. Select relevant features (genres, keywords, overview)
3. Combine text data into a single column
4. Convert text into numerical vectors using TF-IDF
5. Compute similarity using cosine similarity
6. Take user input (movie name)
7. Recommend top similar movies

---

## ▶️ How to Run

### 1️⃣ Install Dependencies

```bash
pip install pandas numpy scikit-learn
```

### 2️⃣ Run the Script

```bash
python movie_recommender.py
```

### 3️⃣ Enter Movie Name

```
Enter a movie name: Avatar
```

---

## 📸 Sample Output

```
Movies similar to 'Avatar':

1. Guardians of the Galaxy
2. John Carter
3. Star Trek
4. The Fifth Element
5. Alien
```

---

## 💡 Future Improvements

* 🔥 Add collaborative filtering (user-based recommendations)
* 🌐 Build a web app using Streamlit
* 🎯 Add fuzzy matching for better input handling
* 🤖 Use deep learning models for better accuracy

---

## 🎯 Project Use Cases

* Movie streaming platforms
* Recommendation engines
* NLP-based applications
* Data Science & ML portfolio projects

---

## 👨‍💻 Author

**Pranjil Kumar**
CSE (Data Science & Analytics) Student

---

## 📜 License

This project is for educational purposes.
