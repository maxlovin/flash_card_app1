# 🇫🇷 Flashy - French-English Flashcard Application

A GUI flashcard learning application built with Python's `tkinter` and `pandas`. Uses spaced repetition principles by tracking known words and exporting remaining target vocabulary to a local dataset for future practice sessions.

---

## 📌 Features

* **Timed Card Flip:** Automatically flips the flashcard after 3 seconds (3000 ms) to display the English translation.
* **Progress Persistence:** Removes correctly guessed words from the active deck and saves remaining vocabulary to `data/words_to_learn.csv`.
* **Smart Data Fallback:** Automatically loads original dataset (`french_words.csv`) if no saved progress file exists.
* **Custom Graphical Cards:** Canvas rendering with front/back card artwork and themed control buttons.

---

## 🛠️ Prerequisites & Setup

### 1. Requirements
* Python 3.x installed.
* `pandas` library.

### 2. Directory Structure & Assets
Ensure the required CSV datasets and PNG image files exist relative to your script:

```text
flashcard-app/
│
├── main.py
├── data/
│   └── french_words.csv
└── images/
    ├── card_front.png
    ├── card_back.png
    ├── right.png
    └── wrong.png
