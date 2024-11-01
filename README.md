# 3D Calculator

A visually appealing, animated 3D calculator built with HTML, CSS, and JavaScript. The calculator supports basic arithmetic operations, such as addition, subtraction, multiplication, and division. It also includes a glow animation when the equal button is pressed for a modern user experience.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Keyboard Shortcuts](#keyboard-shortcuts)
- [AI Assistance](#ai-assistance)
- [Acknowledgments](#acknowledgments)

## Features

- **3D Interactive Design**: The calculator buttons have a 3D appearance and respond to clicks and keypresses with animations.
- **Basic Arithmetic Operations**: Supports addition, subtraction, multiplication, and division.
- **Keyboard Accessibility**: The calculator can be operated using keyboard shortcuts.
- **Glow Animation**: Upon pressing the equal (`=`) key, a glow effect highlights each key, creating a ripple effect.
- **Clear & Backspace Functionality**: Clear the entire input with the "C" button or delete the last character with "Backspace".

## Technologies Used

- **HTML5**: Structuring the page content.
- **CSS3**: Styling the calculator with animations, 3D effects, and responsive design.
- **JavaScript**: Adding interactivity, calculations, and keyboard functionality.

## Installation

1. Clone or download the repository.
2. Open the `index.html` file in your preferred web browser.

## Usage

1. **Launching**: Open the `index.html` file in any modern browser.
2. **Entering Numbers**: Click on the buttons or use your keyboard to input numbers.
3. **Arithmetic Operations**: Use the buttons `+`, `-`, `*`, and `/` or the corresponding keys on your keyboard.
4. **Result Calculation**: Press the `=` button or `Enter` key to calculate the result.
5. **Clearing Input**: Use the `C` button to clear all input.
6. **Backspace Functionality**: Use the `Backspace` key to delete the last character.

## Keyboard Shortcuts

| Key      | Action             |
|----------|---------------------|
| `0-9`    | Enter numbers       |
| `+`      | Addition            |
| `-`      | Subtraction         |
| `*`      | Multiplication      |
| `/`      | Division            |
| `=`/`Enter` | Calculate Result |
| `C`      | Clear               |
| `Backspace` | Delete last entry|

## AI Assistance

This project received assistance from AI, specifically to simulate a click effect on calculator keys when a corresponding key is pressed on the keyboard. This enhancement improves user experience by visually aligning physical key presses with on-screen actions.

## Code Explanation

### HTML Structure

- **Calculator Body**: Defined by the `.keyboard` div containing rows of keys (`.row` divs).
- **Display**: An element to show the current input and results.

### CSS Styling

- **3D Effects**: CSS variables define the 3D rotation angles and shadows, providing depth.
- **Responsive Design**: CSS variables allow scaling of the calculator on smaller screens.

### JavaScript Functionality

- **handleInput Function**: Manages all input, whether from the keyboard or the calculator buttons.
- **Animation Effects**: Glow animation triggered after result calculation, highlighting buttons in a ripple effect.

## Acknowledgments

- 3D effects and animations were inspired by modern UI design trends.
- Code was structured for clarity, ease of use, and a responsive user experience.
