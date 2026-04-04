# 🧩 Boggle Game

A Python implementation of the classic **Boggle** word-search game.  
Players form words by connecting adjacent letters on a grid. Words are validated against a dictionary file, and scoring is based on word length.

---

## 📌 Overview

Boggle is played on a grid of letters (commonly 4×4).  
Words must:

- Be at least 3 letters long  
- Be formed from **adjacent letters** (horizontal, vertical, or diagonal)  
- Not reuse the same letter cell within a single word  
- Exist in the provided dictionary (`words.txt`)

This project searches the board for all valid words and calculates the total score.

---

## 🚀 Features

- 📄 Uses a dictionary file (`words.txt`) for word validation
- 🧠 Applies official Boggle-style scoring rules
- 🐍 Written in Python (no external dependencies required)
- 📦 MIT Licensed

---

## 📁 Project Structure

```
Boggle_Game/
│
├── start_boggle.py   # Main game logic
├── words.txt         # Dictionary file
├── LICENSE
├── README.md         # This file
└── .gitignore
```

---

## 🛠 Requirements

- Python 3.x

No additional libraries are required.

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/xuanwei20/Boggle_Game.git
```

2. Navigate into the project folder:

```bash
cd Boggle_Game
```

3. Run the program:

```bash
python start_boggle.py
```

Follow any on-screen prompts (if applicable).

---

## 🧮 Scoring Rules

| Word Length | Points |
|-------------|--------|
| 0–2         | 0      |
| 3–4         | 1      |
| 5           | 2      |
| 6           | 3      |
| 7           | 5      |
| 8+          | 11     |

---

## 📘 How It Works

1. The program generates a Boggle board.
2. Player searches all possible adjacent letter combinations.
3. Valid words found in `words.txt` are collected.
4. The final list of words and total score are displayed.

---

## 💡 Possible Improvements

- Add a graphical user interface (GUI)
- Allow custom board sizes
- Add multiplayer mode
- Add unit testing

---

## 📜 License

This project is licensed under the MIT License.

---

⭐ If you enjoyed this project, feel free to star the repository!
