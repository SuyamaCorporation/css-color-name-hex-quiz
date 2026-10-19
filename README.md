# CSS Named Color to Hex Quiz

An interactive quiz game to master all 147 CSS named colors.

## Features

- **All 147 CSS named colors** hardcoded with hex values
- **2 Game Modes**:
  - Name to Color: see the name, click the correct color swatch
  - Color to Name: see a color swatch, pick the correct CSS name
- **20-second timer** per question with visual countdown bar
- **20 questions** per game, randomly selected
- **Score tracking**: 5 points per correct answer
- **Streak counter** with visual dots
- **Fun facts** about each color shown after every answer
- **High score** stored in localStorage per game mode
- Results screen with accuracy stats and streak records

## Usage

1. Open `index.html` in a modern browser
2. Choose a game mode on the start screen
3. Answer 20 questions as fast as you can
4. See your score and compare against your high score

## Technical Details

- Single-file SPA, no server required
- Tailwind CSS via CDN
- All 147 CSS named colors with hex values and fun facts hardcoded
- localStorage for high score persistence
- XSS-safe rendering throughout
- ARIA labels for accessibility
