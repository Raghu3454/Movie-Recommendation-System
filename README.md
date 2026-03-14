# 🎬 Movie Recommendation System using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Recommendation System](https://img.shields.io/badge/Project-Recommendation%20System-brightgreen)

---

## 📌 Project Overview

The **Movie Recommendation System** suggests movies to users based on their interests.
This project uses **Content-Based Filtering** and **Cosine Similarity** to recommend movies similar to the one selected by the user.

Recommendation systems are widely used in platforms like **Netflix, Amazon Prime, and YouTube** to suggest personalized content.

---

## 🚀 Features

✔ Recommend similar movies instantly

✔ Uses machine learning similarity algorithms

✔ Simple and beginner-friendly project

✔ Demonstrates how recommendation engines work

---

## 🧠 Recommendation Algorithm

### Content-Based Filtering

The system recommends movies that are similar to the movie selected by the user.

Example:

User likes → **Avengers**

Recommended movies:

* Iron Man
* Captain America
* Thor

The similarity between movies is calculated using **Cosine Similarity**.

---

## 🛠️ Technologies Used

* 🐍 Python
* 📊 Pandas
* 🤖 Scikit-learn
* 🔢 NumPy

---

## 📂 Project Structure

```id="m1"
movie-recommendation-system
│
├── movies.csv
├── recommendation.py
├── requirements.txt
└── README.md
```

---

## 📊 Dataset Example

| Title           | Action | Comedy | Drama |
| --------------- | ------ | ------ | ----- |
| Avengers        | 1      | 0      | 0     |
| Iron Man        | 1      | 0      | 0     |
| Captain America | 1      | 0      | 0     |
| Thor            | 1      | 0      | 0     |
| Batman          | 1      | 0      | 1     |

---

## ⚙️ Installation

Clone the repository

```id="m2"
git clone https://github.com/yourusername/movie-recommendation-system.git
```

Move to project folder

```id="m3"
cd movie-recommendation-system
```

Install required libraries

```id="m4"
pip install pandas scikit-learn
```

---

## ▶️ Run the Project

```id="m5"
python recommendation.py
```

Example output:

```id="m6"
Recommended Movies:

Iron Man
Captain America
Thor
```

---

## 📈 How It Works

1️⃣ Load movie dataset using Pandas
2️⃣ Convert movie features into numerical data
3️⃣ Calculate similarity between movies using **Cosine Similarity**
4️⃣ Recommend movies similar to the selected movie

---

## 🔮 Future Improvements

* Add **large movie datasets**
* Create a **web interface using Streamlit**
* Add **user-based recommendation system**
* Build a **Netflix-style recommendation engine**

---

## 👨‍💻 Author

**Raghavendra**
BTech – Artificial Intelligence & Data Science

---

⭐ If you like this project, consider giving it a **star on GitHub!**
