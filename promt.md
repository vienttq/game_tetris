# 🎮 Prompt: Build a Tetris Game (Complete)

## Objective
Create a fully functional Tetris game that runs in a web browser using HTML, CSS, and JavaScript (no external frameworks required unless necessary).

---

## Core Requirements

### 1. Game Mechanics
- Implement classic Tetris gameplay:
  - Falling tetromino shapes (I, O, T, S, Z, J, L)
  - Random piece generation (use fair randomization or "bag system")
  - Rotation system (clockwise at minimum)
  - Collision detection (walls, floor, other blocks)
  - Line clearing when a row is full
  - Gravity (pieces fall automatically over time)
  - Game over condition when new piece cannot spawn

---

### 2. Controls
- Keyboard controls:
  - Left Arrow: Move left
  - Right Arrow: Move right
  - Down Arrow: Soft drop
  - Up Arrow or X: Rotate
  - Space: Hard drop
  - P: Pause / Resume game

---

### 3. UI / Layout
- Create a clean game interface including:
  - Main game board (grid 10x20)
  - Score display
  - Level display
  - Lines cleared counter
  - Next piece preview
  - Optional: Hold piece feature

---

### 4. Scoring System
- Score increases based on lines cleared:
  - 1 line = 100 points
  - 2 lines = 300 points
  - 3 lines = 500 points
  - 4 lines (Tetris) = 800 points
- Increase level every 10 lines
- Increase falling speed as level increases

---

### 5. Visual Design
- Use different colors for each tetromino
- Add simple animations for:
  - Line clear
  - Piece drop
- Use clean and modern styling with CSS
- Center the game on screen

---

### 6. Code Structure
- Separate logic into clear sections:
  - Game state
  - Rendering
  - Input handling
  - Game loop
- Use requestAnimationFrame for smooth rendering
- Keep code modular and readable

---

### 7. Bonus Features (Optional but Recommended)
- Sound effects (move, rotate, line clear)
- Mobile support (touch controls)
- Save high score using localStorage
- Ghost piece (shows landing position)

---

## Output Format
- Provide full working code in a single HTML file
- Include embedded CSS and JavaScript
- Ensure code runs immediately when opened in browser

---

## Quality Expectations
- No major bugs in movement or collision
- Smooth gameplay performance
- Clean, well-commented code
- Responsive and user-friendly interface

---

## Extra Instruction
- If possible, optimize performance for low-end devices
- Avoid unnecessary libraries
- Ensure the game loop is efficient and stable
