

# 🎯 Nerdle — Terminal Equation-Guessing Game 🧮

Nerdle is a compact, terminal-based equation-guessing game inspired by Wordle but focused on arithmetic equations. Guess the hidden equation within a limited number of attempts and receive per-symbol feedback after every guess.

## 🔎 What it does

- 🔢 Generates or accepts arithmetic equations composed of digits, operators (+, -, *, /), and an equals sign (`=`).
- ✅ Validates guesses and compares them to the target equation.
- 🎯 Displays feedback for each character: correct & correct position, correct but wrong position, or not present.

## 📁 Project structure

- `nerdle.py` — 🕹️ CLI entry point to play the game.
- `game_engine.py` — ⚙️ Core game logic (guess validation and feedback).
- `equation_generator.py` — 🔢 Random valid equation generator.
- `tests/` — 🧪 Unit tests (use `pytest` to run).

## ⚙️ Requirements

- 🐍 Python 3.8 or newer (3.10+ recommended).
- 📦 No external dependencies — uses only the Python standard library.

## ▶️ Quick start

1. From the project root, run:

```bash
python3 nerdle.py
```

2. Enter guesses following the prompts. Each guess must be a valid equation (for example `12+3=15`). The game responds with feedback after each attempt.

## 🧪 Running tests

Run the tests with pytest:

```bash
pytest -q
```

This will run unit tests for the equation generator, game engine, and top-level behavior.

---


