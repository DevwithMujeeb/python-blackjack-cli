# 🃏 Python Blackjack (CLI)

A command-line Blackjack game built in Python using object-oriented programming principles.

This project simulates a simplified Blackjack experience directly in the terminal. It includes full deck management, dealer logic, Ace handling, win detection, and multi-round gameplay.

---

## 📌 Features

- 52-card deck generation
- Automatic deck shuffling
- Player vs Dealer gameplay
- Dealer AI (hits until 17+)
- Proper Ace value adjustment (11 → 1 when needed)
- Blackjack detection
- Bust detection
- Multi-round support
- Clean OOP structure

---

## 🏗 Project Structure

The game is structured using the following classes:

- `Card` → Represents a single card
- `Deck` → Generates and manages the card deck
- `Hand` → Handles player/dealer cards and value calculation
- `Game` → Controls overall gameplay logic

---

## ▶️ How to Run

Make sure Python 3.x is installed.

```bash
python main.py
```

or

```bash
py main.py
```

---

## 🎮 How to Play

1. Enter the number of games you want to play.
2. You will receive two cards.
3. Choose:
   - `hit` (or `h`) → draw another card
   - `stand` (or `s`) → end your turn
4. Dealer draws until reaching 17 or higher.
5. Winner is determined automatically.

Goal: Get as close to **21** as possible without going over.

---

## 🧠 Game Rules

| Card Type    | Value                         |
| ------------ | ----------------------------- |
| Number cards | Face value                    |
| J, Q, K      | 10                            |
| Ace          | 11 (or 1 if total exceeds 21) |

---

## 📚 Concepts Demonstrated

- Object-Oriented Programming (OOP)
- Class design and encapsulation
- Method interaction
- Game loop control
- Input validation
- Basic AI logic
- Exception handling

---

## 🚀 Future Improvements

- Betting system
- Score tracking
- Save player statistics
- GUI version (Tkinter / Pygame)
- Web-based version

---

## 📄 License

This project is open-source and available under the MIT License.
