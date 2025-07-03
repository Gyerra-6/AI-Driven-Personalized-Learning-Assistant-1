# AI-Driven Personalized Learning Assistant

This project is an AI-powered platform that offers **personalized learning support** by generating questions from your materials, evaluating answers, and tracking progress—ideal for students, educators, and lifelong learners.

---

## Key Features

- **Document Upload & Parsing** – Upload PDFs, text files, or documents for use as learning content.
- **Question Generation** – Automatically generates quizzes based on content using NLP/LLM methods.
- **Answer Evaluation & Feedback** – Provides immediate, detailed feedback to learners.
- **Progress Tracking** – Monitors performance over time and identifies areas for improvement.
- **Adjustable Settings** – Configure difficulty level, question formats, and learning preferences.
- **End-to-End ML Pipeline** – Combines NLP model inference (question generation, answer checking) with feedback loop.

---

## What the Project Does

This platform helps learners by:

1. Uploading and parsing study materials.
2. Generating relevant quiz questions using AI.
3. Letting users attempt quizzes and receive instant feedback.
4. Storing results to provide personalized insights and track improvement.

---

## How to Run the Project

## Prerequisites

- **Languages & Frameworks**: Python 3.8+, FastAPI backend, and, optionally, Streamlit frontend.
- **Databases / Storage**: MongoDB or SQLite.
- **AI Libraries**: HuggingFace Transformers, PyTorch/TensorFlow, or OpenAI API.

## Build & Execute

```bash
# Clone the repo
git clone https://github.com/Gyerra-6/AI-Driven-Personalized-Learning-Assistant-1.git
cd AI-Driven-Personalized-Learning-Assistant-1

# Create venv & install dependencies
python3 -m venv venv && source venv/bin/activate
pip install -r requirements.txt

# Run backend server
uvicorn backend.main:app --reload

# (Optional) Run frontend UI
streamlit run frontend/app.py
```

---

Check the /examples directory for sample upload and quiz flows once services are running.

Folder Structure & Key Files
/
├── backend/               # FastAPI server (uploads, NLP, evaluation)
├── frontend/              # Optional Streamlit or React UI
├── models/                # Trained models or inference pipelines
├── data/                  # Sample documents and quizzes
├── utils/                 # Helpers for parsing, evaluation, scoring
├── requirements.txt
└── README.md

---

## Roadmap & Potential Improvements
- Add adaptive difficulty scaling based on user performance.
- Integrate speech recognition for spoken quiz responses.
- Enhance feedback with concept visualization and hints.
- Build teacher dashboard to track and manage multiple learners.
- Deploy as Docker containers via CI/CD pipelines.

---

Contact & Support
Have questions, feedback, or want to collaborate?

Open an issue on GitHub

Or email: gayathriyerra3@gmail.com

---

This project combines AI-driven quizzes, intelligent evaluation, and learner analytics to deliver a rich, personalized learning experience.

Feel free to tailor details like model paths, endpoints, or technologies according to your actual setup. Let me know if you want help exporting this as a `.md` file, adding badges (e.g., build status or license), or adjusting it for a classroom or publication audience!
::contentReference[oaicite:0]{index=0}
