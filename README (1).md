# 🍽️ AI Chef - Personalized Recipe Generator using AI & Machine Learning

Welcome to **AI Chef**, a machine learning-powered project that recommends personalized recipes based on user preferences and available ingredients. It also generates nutritional insights and offers a demo web app to explore recipes using AI.

---

## 📌 Project Highlights

- ✅ Machine Learning-based Recipe Recommendation Engine
- ✅ NLP on ingredients & food titles using TF-IDF & Cosine Similarity
- ✅ Interactive Charts: Nutritional Distribution, Cuisine Analysis, Cooking Time, etc.
- ✅ 🧠 AI-Powered Search using Scikit-learn + Streamlit
- ✅ Web App with form-based inputs and live recipe filtering

---

## 📂 Project Structure

```
AI_Chef_Project/
│
├── data/
│   └── recipes_dataset.csv         # Main dataset with over 20,000 recipes
│
├── images/
│   ├── cuisine_distribution.png    # Chart: Cuisine variety
│   ├── ingredient_wordcloud.png    # WordCloud of ingredients
│   ├── nutrition_piechart.png      # Nutritional info (macro/micro)
│   └── cooking_time_histogram.png  # Distribution of cooking time
│
├── app/
│   └── ai_chef_app.py              # Streamlit Web App file
│
├── AI_Recipe_Recommendation.ipynb  # Full Jupyter Notebook analysis
├── requirements.txt                # Python dependencies
└── README.md                       # Project overview
```

---

## 🧠 Model Overview

The core logic of the model involves:

- **TF-IDF Vectorization** on recipe titles and ingredients
- **Cosine Similarity** to compute the closest recipe matches
- **Pandas & Matplotlib** for data wrangling and visualization
- **Streamlit** to serve as a front-end user interface

---

## 🚀 How to Run

### 🛠️ Prerequisites

```bash
pip install -r requirements.txt
```

### 📊 Launch Jupyter Notebook

```bash
jupyter notebook AI_Recipe_Recommendation.ipynb
```

### 🌐 Run the Web App

```bash
cd app
streamlit run ai_chef_app.py
```

---

## 📈 Sample Visualizations

- ✅ Cuisine Distribution
- ✅ Word Cloud of Ingredients
- ✅ Cooking Time Histogram
- ✅ Nutritional Macro Pie Chart

_All charts are in the `/images` folder and auto-generated during notebook execution._

---

## 🔍 Dataset Info

- Source: Kaggle public dataset, enhanced with synthetic nutrition data
- Size: ~20,000+ recipes
- Fields: `title`, `ingredients`, `cuisine`, `nutrition`, `cooking_time`, `steps`

---

## ✨ Live Demo Preview

You can launch the **AI Chef Streamlit Web App** locally to explore recipes dynamically by:

- Selecting a cuisine
- Filtering by time or ingredients
- Viewing matching recipes with nutrition breakdown

---

## 🤝 Contributing

Pull requests welcome! For major changes, please open an issue first to discuss what you would like to change.

---

## 📬 Contact

For questions, contact: [yourname@email.com]

---

## 📜 License

This project is licensed under the MIT License - see the LICENSE file for details.

---

🧑‍🍳 Bon Appétit with AI Chef!