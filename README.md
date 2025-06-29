# 🎓 AI Career Recommender

An intelligent NLP-powered web app that suggests suitable career paths based on a user's interests and skills. Built using Python, NLTK, Scikit-learn, and Streamlit.

> 🔍 Helps students and job seekers explore personalized career options interactively.

---

## 🚀 Live Demo

👉 [Try the App on Streamlit Cloud](https://ai-career-recommender.streamlit.app)

---

## 📌 Features

- 🧠 Machine Learning model trained on real-world career data
- 💬 Understands natural language input like "I love designing apps
- 🎯 Suggests careers like Software Developer, Doctor, Designer, etc.
- 🎛️ Built-in example buttons for easy testing
- 📱 Fully interactive and deployable with Streamlit

---

## 🧠 How It Works

1. User enters their **interests and skills**
2. The app:
   - Preprocesses text using NLTK (lemmatization, stopwords)
   - Transforms text using TF-IDF
   - Classifies using a Logistic Regression model
3. Returns the **most likely career path**

---

## 🗂️ Project Structure

| File                         | Description              |
|------------------------------|--------------------------|
| `streamlit_app.py`           | Main Streamlit app       |
| `career_recommender.pkl`     | Trained ML model         |
| `requirements.txt`           | Python dependencies      |
| `README.md`                  | Project documentation    |

---

## ⚙️ Setup Instructions (Run Locally)

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/AI-Career-Recommender.git
cd AI-Career-Recommender
```

### 2. Create & Activate Virtual Environment

```bash
python -m venv .venv
.\.venv\Scripts\activate   # Windows
```

### 3. Install Requirements

```bash
pip install -r requirements.txt
```

### 4. Run the App

```bash
streamlit run streamlit_app.py
```

Open http://localhost:8501 in your browser 🎉

### 📦 requirements.txt

```
streamlit
nltk
scikit-learn
joblib
```

---

## 🌐 Deployment on Streamlit Cloud

1. Push this project to a public GitHub repo
2. Go to https://streamlit.io/cloud
3. Connect GitHub → Select this repo → Set main file to streamlit_app.py
4. Deploy ✅

---

## 🧪 Sample Inputs to Try

- "I enjoy coding and app development"
- "I am passionate about biology and healthcare"
- "I like drawing, painting, and digital art"
- "I love working with numbers and accounts"
- "I enjoy managing people and events"

---

## 🙋‍♂️ Author

Chandan Maurya  
🎓 B.Tech (CSE), Guru Nanak Dev Engineering College  
🔗 [GitHub](https://github.com/chandan-911)  
🔗 [LinkedIn](https://www.linkedin.com/in/chandan-m911/)  

---

## 📄 License

Licensed under the MIT License

---

✨ “Choose a job you love, and you will never have to work a day in your life.” – Confucius