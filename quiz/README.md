# Terminal Trivia Quiz Game (Open Trivia DB API)

## 📌 Project Overview
An interactive command-line trivia game powered by the **Open Trivia Database (OpenTDB) REST API**. The application dynamically retrieves trivia questions based on user-selected criteria (number of questions, category, difficulty, and question type), presents randomized answer choices, and calculates a final score.

---

## ✨ Features
- Live API integration with Open Trivia DB (`https://opentdb.com/api.php`).
- Multiple categories and difficulty levels (Easy, Medium, Hard).
- Multiple-choice and True/False question support.
- HTML entity decoding for clean question formatting in the terminal.
- Dynamic score tracking and final performance summary.

---

## 📦 Requirements & Installation
Install the required HTTP library:

```bash
pip install -r requirements.txt
```

### Dependencies
- `requests` - Fetches dynamic trivia questions and JSON payloads
- Python standard library: `html`, `random`

---

## 🚀 How to Run
Run the quiz script from your terminal:

```bash
python quiz.py
```
Follow the on-screen prompts to choose answers and complete the trivia challenge!
