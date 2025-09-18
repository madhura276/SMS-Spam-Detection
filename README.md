# 📩 SMS Spam Detection

A machine learning project to classify SMS messages as **Spam** or **Ham** using **Naive Bayes**.

---

## 📌 Dataset
- Dataset: [SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection)
- 5,574 messages labeled as `ham` (legit) or `spam`.

---

## ⚙️ Steps
1. Data loading & preprocessing
2. Train-test split
3. Text vectorization using **CountVectorizer**
4. Model training using **Naive Bayes**
5. Evaluation (Accuracy, Confusion Matrix, Classification Report)
6. Testing on new sample messages

---

## 📊 Results
- Accuracy: ~98%
- High precision & recall for spam detection.

---

## 🚀 Tech Stack
- Python
- Pandas, Scikit-learn
- Matplotlib / Seaborn (for visualization)

---

## 📜 How to Run
```bash
# Clone repo
git clone https://github.com/madhura276/sms-spam-detection.git
cd sms-spam-detection

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
