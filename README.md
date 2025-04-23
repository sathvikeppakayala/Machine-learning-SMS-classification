# 📩 SMS Spam Classifier

A machine learning-based desktop application that identifies **spam messages** from legitimate ones using a **stacked ensemble model** and **TF-IDF vectorization**. This project combines robust modeling with an intuitive Tkinter GUI to deliver real-time classification results.

![Output Screenshot](output_image.png) <!-- Replace with your actual GUI image filename -->

---

## 🚀 Features

- ⚙️ **Stacked Ensemble Model**: Integrates Logistic Regression, Decision Tree, KNN, AdaBoost, and Random Forest for enhanced accuracy.
- 📊 **TF-IDF Vectorizer**: Converts SMS text into meaningful numeric features.
- 🖥️ **Tkinter GUI**: Provides a simple interface to enter messages and receive instant predictions.
- 📦 **Pickle Integration**: Saves and loads models efficiently for reuse.
- 🔒 **Accurate and Reliable**: Delivers strong performance using validated metrics like accuracy, precision, recall, and F1-score.

---

## 🧠 Model Architecture

```text
Raw SMS Text
      │
      ▼
TF-IDF Vectorizer (tfidf_grow.pkl)
      │
      ▼
Stacked Classifier (spam_grow.pkl)
      │
      ▼
Prediction (Spam or Ham)
🛠️ Tech Stack
Language: Python 🐍

Libraries: scikit-learn, pandas, numpy, tkinter, pickle

Modeling Techniques:

Logistic Regression

Decision Tree Classifier

K-Nearest Neighbors

AdaBoost Classifier

Random Forest Classifier

StackingClassifier as the meta-model

📸 Output Interface (GUI)
Here’s how the GUI looks after prediction:

<!-- Replace with your actual GUI image filename -->

🧪 How to Run the Project
Clone the Repository

bash
Copy
Edit
git clone https://github.com/yourusername/spam-classifier.git
cd spam-classifier
Install Requirements

bash
Copy
Edit
pip install -r requirements.txt
Run the GUI

bash
Copy
Edit
python spam_gui.py
Enter any SMS message, click Predict, and see the result!

📁 Project Structure
bash
Copy
Edit
📦 spam-classifier
├── spam.csv                    # Dataset
├── spam_grow.pkl               # Saved Stacking Model
├── tfidf_grow.pkl              # Saved TF-IDF Vectorizer
├── spam_gui.py                 # Tkinter-based GUI App
├── model_training.ipynb        # Jupyter Notebook with full training pipeline
├── output_image.png            # GUI output screenshot
└── README.md                   # This file
📈 Model Evaluation

Model	Accuracy	Precision	Recall	F1-Score
Logistic Regression	✔️	✔️	✔️	✔️
Decision Tree	✔️	✔️	✔️	✔️
KNN	✔️	✔️	✔️	✔️
AdaBoost	✔️	✔️	✔️	✔️
Random Forest	✔️	✔️	✔️	✔️
Stacking Model	⭐ Best	⭐ Best	⭐ Best	⭐ Best
👨‍💻 Author
Sathvik Eppakayala
B.Tech in Computer Science and Technology | Data Science Specialization
📫 Connect with me: LinkedIn | GitHub

📜 License
This project is licensed under the MIT License - feel free to use it for academic or personal projects.

❤️ Contributions
Have an idea to improve this project?
Feel free to fork and submit a pull request!

🔍 References
UCI Machine Learning Repository – SMS Spam Collection

scikit-learn Documentation

Python’s Tkinter Library

yaml
Copy
Edit

---

✅ After pasting it on GitHub, just rename your GUI image to `output_image.png` or update the filename accordingly in the `![Tkinter Output]()` section.

Let me know if you want me to generate the `requirements.txt` too!







