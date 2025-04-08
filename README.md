# 🕹️ Tic-Tac-Toe Game in Go

This is a simple terminal-based **Tic-Tac-Toe (XO)** game implemented in the Go programming language. Two players can play against each other by choosing cell numbers on a 3x3 board.

---

## 📦 Features

- ✅ Two-player turn-based gameplay
- ✅ Board display with placeholder positions
- ✅ Input validation for available cells
- ✅ Automatic winner check (rows, columns, diagonals)
- ✅ Draw detection
- ✅ Play again option after a match

---

## 🧩 How to Play

Each cell on the board is labeled with a number from 1 to 9:

<pre>    
  <1>|<2>|<3>
  ---+---+---
  <4>|<5>|<6>
  ---+---+--- 
  <7>|<8>|<9>
</pre>


### 🕹️ Player Turns:
1. Player X starts the game.
2. Enter a number corresponding to an available spot.
3. The board updates automatically.
4. First player to align three of their symbols (`X` or `O`) in a row, column, or diagonal wins!

If all cells are filled and no one wins, the game ends in a draw.

---

## 🛠️ How to Run

### 🔧 Requirements:
- Go installed (v1.18 or above recommended)

### 🚀 Run the Game:

```bash
go run main.go





