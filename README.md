# TJ-Task-2026-Nikhil-kumar
my project on multimodal real time interaction . 3 distinct things( speech to text (transcription) a language model(brain)and text to speech (voice ).
voice_assistant_project/
│
├── app.py
├── README.md
├── requirements.txt
├── .env.example
├── .gitignore
│
└── screenshots/
    └── README.md
    screenshots/
├── 01_running_app.png
├── 02_user_speech_and_transcript.png
└── 03_ai_response.png
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
$env:OPENAI_API_KEY="YOUR_API_KEY"
python app.py
