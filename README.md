# 🤖 AI-Powered Code Review Assistant (Gradio)

Deploy-ready version of the Colab project as a **Hugging Face Space**.

## 🚀 Quick Deploy (Hugging Face Spaces)

1. Create a new Space → Type: **Gradio**.
2. Add these files: `app.py`, `requirements.txt`, `README.md`.
3. In your Space, go to **Settings → Variables and secrets** and add:
   - Key: `GEMINI_API_KEY` — Value: your Google Gemini API key.
4. The Space builds and gives you a public URL.

> If you don't set `GEMINI_API_KEY`, the app still works with **static analysis only**.

## 🖥️ Run Locally

```bash
python -m venv .venv && source .venv/bin/activate   # Windows: .venv\Scripts\activate
pip install -r requirements.txt
export GEMINI_API_KEY=YOUR_KEY                       # Windows: set GEMINI_API_KEY=YOUR_KEY
python app.py
```

## 📁 Files
- `app.py` — Gradio app
- `requirements.txt` — Python dependencies
- `README.md` — This guide