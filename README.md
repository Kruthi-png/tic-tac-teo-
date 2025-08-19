#  Tic-Tac-Toe Game

A responsive, accessible, and visually appealing Tic-Tac-Toe game built using **HTML**, **CSS**, and **JavaScript**. This project demonstrates DOM manipulation, event handling, and game logic implementation in a clean and interactive UI.

## Features

- **Two-player mode** (Player X vs Player O)
- **Win detection** with visual highlights
- **Draw detection**
- **Game reset** functionality
- **Responsive design** for mobile and desktop
- **Accessible markup** using ARIA roles and labels

## Technologies Used

- HTML5
- CSS3 (with Flexbox and Grid)
- JavaScript (ES6+)
- Google Fonts: [Inter](https://fonts.google.com/specimen/Inter)

## File Structure

## How to Run

1. Clone or download the repository.
2. Open `index.html` in any modern browser.
3. Start playing by clicking on the cells!

## Accessibility Highlights

- Uses `role="grid"` and `role="gridcell"` for semantic structure.
- `aria-label` dynamically updates to reflect cell state.
- `aria-live="polite"` ensures screen readers announce game status changes.

## Game Logic Overview

- **Board State**: Managed as a 9-element array.
- **Turns**: Alternates between 'X' and 'O'.
- **Winning Conditions**: Checked against predefined combinations.
- **Draw**: Triggered when all cells are filled without a winner.

## Reset Function

Click the **Restart Game** button to:
- Clear the board
- Reset player turn to 'X'
- Restore default styles and labels

## Responsive Design

- Optimized for screens as small as 480px.
- Grid and cell sizes adjust for better touch interaction.

## Customization Ideas

- Add score tracking
- Include AI opponent
- Animate winning line
- Add sound effects

## License

This project is open-source and free to use for educational or personal purposes.

---

Made with 💜 by Kruthi
