# UMAR-AI-Academic
UMAR AI - Premier Academic Intelligence: An offline-first, privacy-focused academic engine powered by local Mistral 7B. Features an "Ultra-Minimal Elite" UI, Master Solver for doubts, intelligent summarization, and a Formula Vault. Built with Python (Flask) &amp; JavaScript.
# 💎 UMAR AI – Premier Academic Intelligence

**The Elite Offline Academic Engine for the Modern Scholar.**

UMAR AI is a cutting-edge, privacy-first academic assistant designed to run entirely offline on your local machine. By leveraging a CPU-optimized Mistral 7B model, it delivers high-precision answers, intelligent summarization, and doubt resolution without needing an internet connection.

Wrapped in an **"Ultra-Minimal Elite"** interface (Stone Grey × Ink Black), UMAR AI removes distractions, focusing purely on academic excellence.

## 🚀 Key Features

* **🧠 Master Solver:** A personal AI tutor for Physics, Math, and Chemistry. Handles complex queries with first-principles logic.
* **📝 Smart Summarizer:** Instantly condenses lengthy texts and documents into high-yield revision notes.
* **⚡ Offline & Secure:** Powered by `llama.cpp` locally. Your data never leaves your device.
* **🎨 Elite UI:** A distraction-free, glassmorphism-inspired interface with smooth typing animations and a premium aesthetic.
* **🗣️ Auto-Read (TTS):** Integrated Text-to-Speech for auditory learning.
* **📂 Formula Vault:** Dedicated section for extracting and managing scientific formulas from PDFs.

## 🛠️ Tech Stack

* **Backend:** Python (Flask), `llama-cpp-python`, `PyMuPDF`
* **Frontend:** HTML5, CSS3 (Tailwind), JavaScript (Vanilla)
* **AI Model:** Mistral 7B Instruct (GGUF format)
* **Design:** Custom "Ultra-Minimal Elite" Theme

## 📥 Installation

1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/yourusername/umar-ai.git](https://github.com/yourusername/umar-ai.git)
    cd umar-ai
    ```

2.  **Install Dependencies:**
    ```bash
    pip install -r backend/requirements.txt
    ```

3.  **Setup Model:**
    * Download `mistral-7b-instruct-v0.2.Q4_K_M.gguf`.
    * Place it in `models/mistral/`.
    * Create a `.env` file and set `MISTRAL_MODEL_PATH`.

4.  **Run:**
    ```bash
    python backend/main.py
    ```

---
*Architect Your Academic Future.*
