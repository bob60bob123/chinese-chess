# Chu Han Zhen Xiong - Chinese Chess

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/HTML5-Game-orange.svg" alt="HTML5">
</p>

**Chu Han Zhen Xiong** is a pure HTML5 implementation of Chinese Chess. No external dependencies required. Runs directly in the browser, supporting both human-vs-human and human-vs-AI gameplay.

[English](README.md) | [简体中文](README_zh-CN.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md)

---

## Features

### Chess Rules
- ✅ Complete Chinese Chess rule implementation
- ✅ 7 piece types: General, Advisor, Elephant, Chariot, Horse, Cannon, Soldier
- ✅ Horse blocking and elephant blocking rules
- ✅ Generals facing rule
- ✅ Check, checkmate, and stalemate detection

### Game Modes
- 🔹 **Human vs Human** - Two players on the same device
- 🔹 **Human vs AI** - Play against AI with three difficulty levels

### AI Difficulty Levels
| Level | Description |
|-------|-------------|
| Beginner | For beginners, AI may make mistakes |
| Intermediate | Basic attack and defense awareness |
| Expert | Strong in positioning and tactics |

### Additional Features
- 🎵 Sound effects for moves, captures, and check alerts
- 📜 Move history
- ↩️ Undo functionality
- 🔄 Restart game

---

## How to Play

### Method 1: Direct Open
Double-click the `index.html` file and open it in any modern browser.

### Method 2: Local Server
```bash
# Python 3
python -m http.server 8080

# Node.js
npx serve .

# PHP
php -S localhost:8080
```
Then visit `http://localhost:8080`

---

## Technical Stack

| Technology | Description |
|------------|-------------|
| HTML5 | Semantic structure |
| CSS3 | Board styling, animations |
| JavaScript | Game logic, AI, interaction |
| Canvas/SVG | Board rendering |

- **Zero Dependencies** - Pure native implementation
- **Responsive** - Adapts to desktop and mobile
- **Accessible** - ARIA label support

---

## Browser Compatibility

| Browser | Supported Version |
|---------|-------------------|
| Chrome | 80+ |
| Firefox | 75+ |
| Safari | 13+ |
| Edge | 80+ |

---

## Project Structure

```
chinese-chess/
├── index.html        # Main page (contains all code)
├── SPEC.md          # Project specification
├── README.md         # English
├── README_zh-CN.md   # Simplified Chinese
├── README_ja.md      # Japanese
├── README_ko.md      # Korean
├── README_es.md      # Spanish
├── LICENSE           # MIT License
└── .gitignore        # Git ignore file
```

---

## Development

### Run Tests
Execute in browser console:
```javascript
runSelfTests()
```

### Debug Mode
Visit `index.html?test` to automatically run all tests.

---

## License

This project is licensed under the [MIT License](LICENSE).