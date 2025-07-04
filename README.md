## 📚 InsightClassroom

InsightClassroom is a robust, ML-powered **Student Feedback & Dashboard System** designed to collect, analyze, and classify student feedback for departments and teachers using sentiment analysis. This platform helps educational institutions gain actionable insights into students' opinions, enabling data-driven improvements.

---

## 🚀 Features

✅ User-friendly Registration and Login system  
✅ Intuitive Home page for students to submit feedback  
✅ **ML-based Sentiment Analysis** (Positive, Neutral, Negative) using scikit-learn models  
✅ Feedback linked to specific departments and teachers  
✅ Simple, maintainable Flask backend  
✅ SQLite database integration  
✅ Easy to customize for any educational institution  

---

## 🤖 Machine Learning Component

InsightClassroom includes a **Machine Learning pipeline** trained on labeled feedback data. The workflow is:

1️⃣ Collect labeled feedback samples (Positive/Neutral/Negative).  
2️⃣ Vectorize text using **TF-IDF** with scikit-learn.  
3️⃣ Train a classifier (e.g., Logistic Regression, SVM, Random Forest).  
4️⃣ Save the trained model (`sentiment_model.pkl`) and vectorizer (`vectorizer.pkl`).  
5️⃣ Load the model in your Flask backend to predict the sentiment of new feedback in real time.

---

## 🛠️ Tech Stack

- Python
- Flask (web framework)
- Scikit-learn (ML model training and prediction)
- Pandas
- SQLite (database)
- HTML, CSS (frontend)

---

## 🧠 How It Works

1. **Students** register and log in via the web interface.
2. On the **Home page**, students write feedback, select the relevant department and teacher, and submit.
3. The feedback is processed by the **trained ML sentiment classifier**, categorizing it as Positive, Neutral, or Negative.
4. The system saves the feedback along with its sentiment to the database for analysis.

---



