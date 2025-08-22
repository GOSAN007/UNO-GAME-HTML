# UNO Game HTML

## Overview

A simple UNO game built with HTML that can be played easily in a web browser. This game provides a Japanese-language UNO experience that's accessible and fun.

## Features

- 🎮 **Simple Controls**: Play with just mouse clicks in your browser
- 🗾 **Japanese Interface**: Complete Japanese language support
- 🔊 **Voice Guide**: Audio announcements for card colors and numbers
- 🎯 **Authentic Rules**: Implements UNO declaration, penalties, and challenge rules
- 📱 **Responsive**: Works on PC, tablet, and smartphone

## Game Features

### Basic Functionality
- Player vs CPU 1-on-1 battles
- Follows standard UNO rules
- Voice announcements for card colors and numbers
- Audio guidance for game progress

### Special Cards
- **Skip Card**: Skip opponent's turn
- **Reverse Card**: Reverse turn order (acts as skip in 1v1)
- **Draw 2 Card**: Force opponent to draw 2 cards
- **Wild Card**: Change to any color
- **Wild Draw 4**: Change to any color + force opponent to draw 4 cards

### Advanced Features
- **UNO Declaration**: Press "UNO" button when you have 1 card left
- **Penalty System**: 2-card penalty for forgetting UNO declaration
- **Challenge Rule**: Challenge Wild Draw 4 cards
- **Color Indicator**: Visual display of selected color for wild cards

## How to Play

1. Open `uno-game.html` in your browser
2. The game starts automatically
3. Click on playable cards during your turn
4. Press "UNO" button when you have 1 card left
5. Play all your cards to win!

## Controls

- **Play Card**: Click on the card you want to play
- **UNO Declaration**: Click "UNO" button when you have 1 card
- **Color Selection**: Choose color when playing wild cards
- **Challenge**: Click "Challenge" button against Wild Draw 4
- **Restart**: Click "Restart" button to start a new game
- **Quit**: Click "Quit" button to end the game

## Technical Specifications

- **Languages**: HTML5, CSS3, JavaScript (ES6+)
- **Audio**: Web Speech API (Speech Synthesis)
- **Supported Browsers**: Chrome, Firefox, Safari, Edge
- **Dependencies**: None (single HTML file)

## Installation & Running

### Method 1: Direct Execution
1. Download `uno-game.html`
2. Open in your browser

### Method 2: Local Server
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server
```

Then access `http://localhost:8000/uno-game.html` in your browser

## File Structure

```
uno/
├── uno-game.html    # Main game file
├── README.md        # Japanese README
└── README_EN.md     # This file (English)
```

## License

MIT License

## Author

GOSAN007

## Contributing

Pull requests and issue reports are welcome!

---

**Enjoy playing UNO!** 🎉