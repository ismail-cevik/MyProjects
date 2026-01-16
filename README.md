# 🪨📄✂️ Rock – Paper – Scissors 

This project is a **command-line Rock–Paper–Scissors game** developed in **Python** using **object-oriented programming (OOP)** principles. The player competes against the computer, and the first side to reach the target score wins the game.

This README is written to be fully **GitHub-ready**, clearly explaining setup, requirements, and execution.

---

## 🎯 Game Logic

- The **player** and the **computer** make a move at the same time.
- Moves are represented by single characters:
  - `t` → Rock
  - `k` → Paper
  - `m` → Scissors
- The computer’s move is selected randomly using Python’s built-in `random` module.
- The winner of each round gains **1 point**.
- The first side to reach the predefined **target score** wins the game.

---

## 🧠 Concepts Used

- Object-Oriented Programming (OOP)
- Classes and objects
- Constructor method (`__init__`)
- Loops (`while`)
- Conditional statements (`if / elif / else`)
- Module usage (`random`)
- User input handling
- Modular programming (`main.py` and `oyun.py` separation)

---

## 📁 Project Structure

```
TasKagitMakas/
│
├── oyun.py        # Game logic and TasKagitMakas class
├── main.py        # Entry point of the program
├── README.md      # Project documentation
└── __pycache__/   # Auto-generated Python cache files
```

> ⚠️ Note: The `__pycache__` directory does not need to be uploaded to GitHub and can be excluded using `.gitignore`.

---

## ⚙️ Requirements

This project does **not** use any third-party libraries.

### Required:

- Python **3.8 or higher**
- Standard Python library:
  - `random`

No `requirements.txt` file is necessary.

---

## ▶️ How to Run

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/ismail-cevik/MyProjects.git
```

### 2️⃣ Navigate to the Project Directory

```bash
cd MyProjects/pythonProjects/TasKagitMakas
```

### 3️⃣ Start the Game

```bash
python main.py
```

### 4️⃣ Set the Target Score

The program will ask how many points are needed to win:

```
Oyun kaç puanda bitsin? --> 3
```

The game will then begin 🎮

---

## 🧪 Sample Output

```
Welcome to Rock-Paper-Scissors!
(t=rock, k=paper, m=scissors) Enter your move --> t
Computer's move: m
You win!
Score: Player 1 - Computer 0
```

---

## 🚀 Possible Improvements

- Allow full-word inputs (`rock`, `paper`, `scissors`)
- Store and display game history
- Add simple AI strategy instead of pure randomness
- Create a graphical user interface (GUI) using `tkinter` or `pygame`
- Add multiplayer support

---

## 👤 Developer

**İsmail Çevik**  
Computer Engineering Student  
GitHub: https://github.com/ismail-cevik

---

## 📜 License

This project was developed for educational purposes. It is free to use, modify, and share.

The computer plays randomly. Humans play psychologically. Randomness usually wins. 😄
