# Connect-6 AI Game 🎮🤖

An advanced AI-powered implementation of the **Connect-6** game using Python, Pygame, and classical game theory algorithms.

---

## 🔍 Overview

**Connect-6** is a strategic two-player game and a generalization of Connect-4. Players alternate turns placing **two stones per move** (except the first move) on an `n x n` board. The first to align **six stones in a row**—horizontally, vertically, or diagonally—wins.

This project implements the full game with a GUI and an AI opponent using:
- 🎯 **Minimax Algorithm**
- ⚡ **Alpha-Beta Pruning**
- 🧠 **Two Heuristic Functions** (H1 & H2)

---

## 🎯 Objectives

- Develop a playable **Connect-6** game with GUI using **Pygame**
- Implement and compare **Minimax** and **Alpha-Beta Pruning**
- Design two heuristics:
  - `H1`: Fast, basic win/loss detection
  - `H2`: Smarter, handles multiple threat levels
- Evaluate performance based on:
  - Win/draw rates
  - Response time
  - Depth and strategy

---

## 🧠 AI Logic

### Minimax
A recursive decision-making algorithm that assumes the opponent plays optimally. Explores all possible moves up to a specific depth.

### Alpha-Beta Pruning
Optimization of Minimax that skips unpromising branches, improving speed by up to **75%**.

### Heuristics
- `H1`: Simple evaluation (fast, good for testing)
- `H2`: Complex evaluation (considers 2 to 6-in-a-row patterns, both offense and defense)

---

## 🧪 Experiments

- Tested on board sizes from `6x6` to `12x12`
- Depths from `2` to `8+`
- Results:
  - `H2 + Alpha-Beta` gave the smartest gameplay
  - `H1` is faster but less strategic

---

## ⚙️ Tech Stack

- **Language**: Python 3.x
- **Libraries**:
  - `pygame` — GUI and rendering
  - `numpy` — Game board matrix
  - `tkinter` — Simple input dialogs
  - `math`, `random`, `sys` — Utilities
- **IDE**: PyCharm, Jupyter Notebook

---

## 🚀 Future Enhancements

- Use **Reinforcement Learning** to train AI
- Add **AI difficulty levels**
- Allow **multi-AI tournaments**
- Support for custom board sizes and themes

---


## 📄 References

- [Pygame Docs](https://www.pygame.org/docs/)
- [GeeksforGeeks - Minimax](https://www.geeksforgeeks.org)
- [Connect-6 Research Paper](https://www.researchgate.net/publication/332944251_Design_and_Implementation_of_connect6_Intelligent_Game_System)
- [NumPy Docs](https://numpy.org/)
- [W3Schools](https://www.w3schools.com)

---

## 👨‍💻 Author

**Mohamed Saad**  
[GitHub](https://github.com/mohamed-code342)

---

