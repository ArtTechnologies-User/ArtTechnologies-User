# WAEC Tutor: On‑Device AI for Exam Success

## 📘 Overview
WAEC Tutor is an **offline AI assistant** built for senior secondary school students preparing for WAEC exams.  
It runs locally on budget laptops using a quantized LLaMA model via `llama-cpp`, providing subject coverage, quizzes, and score tracking without internet access.

---

## 🎯 Features
- **Multi‑subject coverage**: Biology, Chemistry, Physics, Mathematics, English, Agric Science, Geography, Economics, Government, Literature, Commerce, Accounting.
- **Interactive Q&A**: Students type questions and receive clear, contextual answers.
- **Quiz Mode**: Generates WAEC‑style multiple choice questions with instant feedback.
- **Score Tracking**: Tracks performance and progress over time.
- **Offline usability**: Runs fully on local laptops without internet.
- **Accessible interface**: Tkinter GUI with subject dropdowns, Ask/Quiz buttons, Clear/Save options.

---

## 🛠 Installation
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/waec-tutor.git
   cd waec-tutor

2. Create a virtual environment:
    ```bash
    python -m venv venv
    venv\Scripts\activate

3. Install dependencies:

    ```bash
    pip install llama-cpp-python
    Place your quantized model file (.gguf) inside the models/ folder.

🚀 Usage
Run Test Script
    ```bash
    python test_llama.py

Launch GUI
    ```bash
    python waec_tutor_gui.py

Type your question in the entry box.
Click Ask to get an answer.
Use Quiz Mode to practice WAEC‑style questions.
Track your score as you answer.   

Author
Taiwo Anthony Alabi  
📧 alabitaiwoanthony@gmail.com
GitHub:github.com/ArtTechnologies-User

<!---
ArtTechnologies-User/ArtTechnologies-User is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
