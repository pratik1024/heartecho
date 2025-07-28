💖 HeartEcho 
An echo of you — across time, space, and soul.

HeartEcho is a poetic fusion of emotional intelligence, storytelling, and cultural data — designed as a web experience where users discover who they are, echoed across time.
At its core, HeartEcho is a personalized narrative generator that creates three unique personas (or “Echo Twins”) based on a user’s tastes, emotions, and personality.

 
🧠 Features
🔐 Smooth Onboarding with OTP Verification
💬 Poetic AI Interviewer (GPT-4)
🔍 Cultural Insight Enrichment (Qloo API)
✨ Echo Twin Generator
🎨 AI-Generated Profile Images
💾 Local Profile Storage


✨ Technologies Used
- Python + Flask — Backend logic and routing  
- HTML + CSS + JS — Frontend experience  
- OpenAI GPT-4 — Conversational intelligence and echo twin generation  
- DALL·E (OpenAI API) — AI image generation  
- Qloo API — Enrichment based on cultural taste graphs  
- JSON — Lightweight data persistence  


📂 Project Structure
💖HeartEcho 
├── data/                 # Stores generated user profiles (JSON)
│   ├── abc.json
│   └── ...
├── Static/
│   ├── chat.js           # Handles frontend chat logic
│   └── style.css         # Styling for UI
├── Templates/
│   ├── chat.html         # Chat interface
│   ├── otp.html          # OTP verification page
│   ├── results.html      # Echo Twin results page
│   └── welcome.html      # Landing page
├── .env                  # Stores API keys (not committed)
├── app.py                # Main Flask app logic
├── profileimage.py       # Profile image generation logic
├── qloo.py               # Qloo enrichment logic
└── requirements.txt      # Required Python packages

🔧 Installation
Clone the repository
git clone https://github.com/pratik1024/heartecho.git
cd heartecho

1. Create and activate a virtual environment
python -m venv venv
source venv/bin/activate    # On Windows use: venv\Scripts\activate

2. Install dependencies
pip install -r requirements.txt

3. Create a .env file with your API keys
   Set up .env file
OPENAI_API_KEY=your_openai_key
QLOO_API_KEY=your_qloo_key

4. 🚀 Run the App
python app.py

5. Then open your browser and visit:
http://127.0.0.1:5000


📸 Screenshots
(Add some screenshots here later like welcome page, chat interface, results.html preview with generated twins and profile images.)

🛡️ Disclaimer
This project is a creative prototype built for learning and exploration. Echo Twins are fictional constructs generated for emotional engagement only.

🙌 Acknowledgments

OpenAI for powering conversational intelligence with GPT-4 and DALL·E
Qloo for providing taste graph enrichment via their API
