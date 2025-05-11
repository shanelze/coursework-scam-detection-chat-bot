# ScamLah – AI-Powered Scam Detection & Education Platform

ScamLah is an AI-driven web application designed to proactively detect scams and educate users in Singapore. Developed as part of the "AI in Accounting & Finance" module at NTU, it integrates machine learning, natural language processing, and generative AI to help users identify, report, and understand scams.

---

## 🚀 Features

- **Real-Time Scam Detection**: Analyze voice, text, and uploaded audio using ML models (Logistic Regression, SVM, Random Forest, Gemini).
- **Personalized Learning Page**: AI-generated videos tailored to scam types encountered by users.
- **Interactive Forum**: Community forum with AI moderation using Gemini to facilitate discussions and advice.
- **ScamMi Chatbot**: A FAQ chatbot powered by Gemini to answer scam-related queries contextually.
- **Gamified Rewards Page**: Leaderboards and engagement stats to encourage continuous learning.
- **Profile Customization**: AI-generated avatars and scam history summary.
- **Cloud Deployment**: Hosted on PythonAnywhere with integrated SQL database.

---

## 🧠 Tech Stack

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Flask, Python
- **Machine Learning**: CountVectorizer, Logistic Regression, Random Forest, SVM, Gemini API, TextBlob
- **Database**: PostgreSQL (Render) / SQLite (PythonAnywhere)
- **APIs**: Google Speech Recognition, NewsAPI, Gemini (Generative AI), InVideo (video generation)

---

## 📦 Installation

```bash
# Clone the repository
git clone https://github.com/your-username/ScamLah.git
cd ScamLah

# Set up virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Set environment variables
export GEMINI_API_KEY=your_api_key
export NEWS_API_KEY=your_api_key

# Run the Flask app
flask run
```

---

## 🔍 Usage

1. Sign up and log in.
2. Upload scam-related content (text, audio, voice).
3. View scam analysis results.
4. Learn from AI-generated scam videos.
5. Join the forum or ask ScamMi your questions.
6. Track your profile progress and compete on the leaderboard.

---

## 📱 Mobile Compatibility

ScamLah is optimized for both desktop and mobile, ensuring accessibility across devices.

---

## 📈 Future Plans

- Expand language support for multi-lingual users.
- Integrate with banking apps and portals.
- Regular scam database updates and legal alert notifications.
- Deeper AI personalization using user trends.

---

## 🔒 License

This project is for educational purposes and currently not under a specific license. Please contact us for collaboration or deployment inquiries.
