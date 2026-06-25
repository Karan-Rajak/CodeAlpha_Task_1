# 🎮 Hangman Game

A simple text-based Hangman game built with Python where the player guesses a hidden word one letter at a time.

---

## 📋 Description

The player tries to guess a randomly selected word by entering one letter at a time. Each wrong guess adds a part to the hangman drawing. The game ends when the player either guesses the full word or runs out of 6 chances.

---

## 🚀 How to Run

Make sure you have Python installed, then run:

```bash
python hangman.py
```

---

## 🎮 How to Play

1. Run the program — a welcome screen will appear
2. A hidden word is randomly selected and shown as underscores `_ _ _ _ _`
3. Enter one letter at a time when prompted
4. Correct letters get revealed in the word
5. Wrong letters are tracked and the hangman drawing builds up
6. You have **6 wrong guesses** before the game is over
7. At the end, you can choose to play again or quit

---

## 📁 Project Structure

```
hangman.py     # Main game file
README.md      # This file
```

---

## 💡 Features

- Random word selection from a predefined list
- ASCII hangman drawing that builds with each wrong guess
- Tracks all guessed letters
- Input validation (single letters only)
- Shows remaining chances after each wrong guess
- Play again option at the end

---

## 🧠 Concepts Used

| Concept | Where Used |
|--------|------------|
| `random` | Picking a random word |
| `while` loop | Main game loop |
| `if-else` | Win/lose/input checks |
| Strings | Displaying and checking letters |
| Lists | Storing guessed letters |

---

## 📝 Word List

The game currently uses these 5 words:

- python
- rocket
- jungle
- castle
- bridge

You can add more words by editing the `words` list in `hangman.py`.

---

## ⚙️ Requirements

- Python 3.x
- No external libraries needed

---

## 👨‍💻 Author

Built as a beginner Python project to practice core programming concepts.
