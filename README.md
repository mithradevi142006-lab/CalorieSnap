# CalorieSnap
AI-powered meal calorie estimator — snap a photo, get instant calories and macros

Snap it. Track it. Enjoy it. 📸

CalorieSnap is an AI-powered meal calorie estimator. Send a photo of your
meal (or describe it in text), and it estimates the calories and macros
using Google Gemini.

## Features
- 📸 Estimate calories from a food photo
- 📝 Works with text descriptions too
- 🍗 Breaks down protein / carbs / fat
- 📊 Summarizes all meals from the conversation
- 📲 Send a WhatsApp report of your daily summary (via Twilio)

## Tech Stack
- Python
- Streamlit (frontend)
- Google Gemini API (AI vision + text)
- Twilio API (WhatsApp messaging)

## How to Run

1. Clone the repo
```bash
git clone https://github.com/mithradevi142006-lab/CalorieSnap.git
cd CalorieSnap
```

2. Install dependencies
```bash
pip install -r requirements.txt
```

3. Add your API keys in `.streamlit/secrets.toml`
```toml
GEMINI_API_KEY = "your_key_here"
TWILIO_ACCOUNT_SID = "your_sid_here"
TWILIO_AUTH_TOKEN = "your_token_here"
```

4. Run the app
```bash
streamlit run app.py
```

## Author
Built by Mithra
