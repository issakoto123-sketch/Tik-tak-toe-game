# ✕ Tic Tac Toe · O

A clean, dark-themed two-player Tic Tac Toe game built with pure HTML, CSS, and JavaScript — no libraries, no dependencies, one single file.

---

## Features

- Two-player local gameplay (X vs O)
- Score tracking across rounds (wins for X, wins for O, draws)
- Animated turn indicator with colored dots
- Win detection with golden highlight and glow effect
- Symbol pop-in animation on placement
- Winning cells pulse to celebrate the victor
- "New Round" resets the board while keeping scores
- "Reset Scores" wipes everything and starts fresh

---

## How to Play

1. Open `tictactoe.html` in any modern web browser — no server needed.
2. Player X always goes first.
3. Players take turns clicking empty cells to place their symbol.
4. The first player to get three in a row (horizontal, vertical, or diagonal) wins.
5. If all 9 cells fill up with no winner, it's a draw.
6. Click **New Round** to play again, or **Reset Scores** to start from zero.

---

## Tech Stack

| Layer      | Technology          | Role                                      |
|------------|---------------------|-------------------------------------------|
| Structure  | HTML5               | Board grid, score cards, buttons          |
| Styling    | CSS3                | Dark theme, animations, responsive layout |
| Logic      | JavaScript (ES6+)   | Game state, win detection, score tracking |
| Fonts      | Google Fonts        | Space Grotesk + Space Mono                |

---

## File Structure

```
tictactoe.html    ← The entire game (HTML + CSS + JS in one file)
README.md         ← This file
```

---

## Win Conditions

The game checks all 8 possible winning lines after every move:

```
Rows:       [0,1,2]  [3,4,5]  [6,7,8]
Columns:    [0,3,6]  [1,4,7]  [2,5,8]
Diagonals:  [0,4,8]  [2,4,6]
```

---

## Browser Support

Works in all modern browsers: Chrome, Firefox, Safari, Edge.
No build step. No installation. Just open and play.
Get the game @ https://issakoto123-sketch.github.io/Tik-tak-toe-game/

---

## License

Free to use, modify, and share.
