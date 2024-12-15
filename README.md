# 📧 SMS and Email Spam Checker

# 🚀 Overview
This project is a Streamlit web app that detects whether an SMS or email message is spam or not.
It uses a machine learning model trained on a dataset of messages to classify new inputs as spam or ham (not spam).

# 🛠️ Features
- Text Classification: Classifies input messages as spam or not spam.
- Machine Learning: Uses the MultinomialNB classifier with TF-IDF vectorization.
- User-Friendly Interface: Built with Streamlit for easy interaction.
- Real-time Results: Instant feedback on message classification.

# 📦 Installation

1. Clone the repository:
   git clone https://github.com/takbir-hasan/Email_Or_SMS_Spam_Checker.git

2. Create a virtual environment:
   python -m venv venv

3. Activate the virtual environment:
  - **On Windows:**
   venv\Scripts\activate
  - **On macOS/Linux:**
   source venv/bin/activate

5. Install dependencies:
   pip install -r requirements.txt'

# ▶️ Running the App
To run the app:
streamlit run app.py

# 🧠 How It Works
How It Works:
1. Preprocessing: Tokenization, stopword removal, and TF-IDF vectorization.
2. Model: Uses the MultinomialNB classifier.
3. Prediction: Displays whether the message is spam or not.

# ⚙️ Dependencies

- streamlit
- scikit-learn
- nltk
- pandas

# 🎯 Future Enhancements

- Support for multiple languages.
- Integration with email APIs.
- Improved UI/UX.

# 📄 License
This project is licensed under the MIT License.

