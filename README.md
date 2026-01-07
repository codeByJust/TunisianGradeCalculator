# 🎓 Tunisian Grade Calculator

A clean, modern, and fully responsive web application for calculating Tunisian high school averages based on the official grading system (out of 20). Built with pure vanilla HTML, CSS, and JavaScript - no frameworks, no dependencies, just open and use.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 📋 Table of Contents

- [Features](#-features)
- [Demo](#-demo)
- [Quick Start](#-quick-start)
- [Grading System](#-grading-system)
- [Usage](#-usage)
- [Technical Details](#-technical-details)
- [Browser Compatibility](#-browser-compatibility)
- [Contributing](#-contributing)
- [License](#-license)

## ✨ Features

### Core Functionality
- **Accurate Tunisian Grading System**: Implements the official coefficient system and weighted exam calculations for all high school subjects
- **10 Subjects Supported**: Math, Physics, STI, Programming, English, French, Arabic, Philosophy, Sport, and Option
- **Real-time Calculations**: Automatic weighted average computation as you type - no submit button needed
- **Pass/Fail Indicator**: Instant feedback on whether you're passing (≥10/20)

### Flexible Input Options
- **Detailed Mode**: Enter individual exam scores (Controls, Synthèse, Oral, TP) with proper weighting
- **Total Only Mode**: Toggle per-subject to enter just the subject average directly
- **Mix & Match**: Use detailed mode for some subjects and total-only for others

### User Experience
- **Dynamic Subject Management**: Enable/disable subjects with checkboxes - disabled subjects are automatically excluded from final calculations
- **Color-Coded Feedback**: 
  - 🟢 Green: ≥12/20 (Excellent)
  - 🟡 Yellow: 10-11.9/20 (Pass)
  - 🔴 Red: <10/20 (Fail)
- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Clean UI**: Modern gradient design with smooth animations and hover effects
- **Results Summary Table**: Detailed breakdown showing subject averages, coefficients, and weighted scores

## 🎯 Demo

[Live Demo](#) *(Add your deployment link here)*

### Screenshots

*Add screenshots of your app here*

## 🚀 Quick Start

### Option 1: Direct Use
1. Download or clone the repository:
```bash
git clone https://github.com/yourusername/tunisian-grade-calculator.git
```

2. Open `index.html` in any modern web browser

3. Start calculating!

### Option 2: Deploy to Vercel/Netlify
Simply connect your GitHub repository to Vercel or Netlify for instant deployment.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/tunisian-grade-calculator)
[![Deploy to Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/yourusername/tunisian-grade-calculator)

## 📊 Grading System

### Subject Coefficients

| Subject | Coefficient |
|---------|-------------|
| Math | 3 |
| Physics | 3 |
| STI | 3 |
| Programming | 3 |
| English | 2 |
| French | 2 |
| Arabic | 2 |
| Philosophy | 1 |
| Sport | 1 |
| Option | 1 |

### Exam Structures & Weights

**Math:**
- Control (×1) + Synthèse (×2)
- Average = (Control + 2×Synthèse) ÷ 3

**Physics:**
- Control (×1) + TP (×1) + Synthèse (×2)
- Average = (Control + TP + 2×Synthèse) ÷ 4

**STI & Programming:**
- Control 1 (×1) + Control 2 (×1) + Synthèse (×2)
- Average = (C1 + C2 + 2×Synthèse) ÷ 4

**English, French, Arabic, Philosophy, Option:**
- Control (×1) + Oral (×1) + Synthèse (×2)
- Average = (Control + Oral + 2×Synthèse) ÷ 4

**Sport:**
- Control (×1) + Synthèse (×2)
- Average = (Control + 2×Synthèse) ÷ 3

### Final Average Calculation
```
Final Average = Σ(Subject Average × Coefficient) ÷ Σ(Coefficients)
```

**Pass Threshold**: 10.00/20

## 💡 Usage

### Basic Usage

1. **Enter Grades**: Type your exam scores (0-20) in the input fields
2. **Toggle Subjects**: Uncheck subjects you don't want to include
3. **Switch Modes**: Use "Total Only" toggle if you only know the subject average
4. **View Results**: See real-time calculations in the results table below

### Tips

- Leave exam fields empty (or 0) if you haven't taken that exam yet
- Use the "Total Only" mode for quick calculations
- Disable optional subjects you're not taking
- The calculator works offline - bookmark it for quick access!

## 🛠️ Technical Details

### Built With
- **HTML5**: Semantic markup
- **CSS3**: 
  - Flexbox & Grid for layouts
  - CSS Variables for theming
  - Smooth animations and transitions
  - Media queries for responsiveness
- **JavaScript (ES6+)**:
  - Vanilla JS, no frameworks
  - Event-driven architecture
  - Real-time DOM manipulation
  - Modular code structure

### Project Structure
```
tunisian-grade-calculator/
│
├── index.html          # Main HTML file with embedded CSS & JS
└── README.md           # This file
```

### Code Highlights
- **No Dependencies**: Zero external libraries or frameworks
- **Lightweight**: Single HTML file (~15KB)
- **Well Commented**: Clear code documentation
- **Modular Design**: Reusable functions for easy maintenance
- **State Management**: Simple object-based state tracking

## 🌐 Browser Compatibility

| Browser | Supported |
|---------|-----------|
| Chrome | ✅ Latest |
| Firefox | ✅ Latest |
| Safari | ✅ Latest |
| Edge | ✅ Latest |
| Opera | ✅ Latest |
| Mobile Browsers | ✅ iOS Safari, Chrome Mobile |

**Minimum Requirements**: Any modern browser with ES6 support

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Add more subject options
- Implement data persistence (localStorage)
- Add print/export functionality
- Create a dark mode toggle
- Add multiple trimester tracking
- Translate to French/Arabic

## 🐛 Bug Reports

Found a bug? Please open an issue with:
- Browser and version
- Steps to reproduce
- Expected vs actual behavior
- Screenshots (if applicable)

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

- GitHub: [@yourusername](https://github.com/codeByJust)

## 🙏 Acknowledgments

- Built for Tunisian students and educators
- Inspired by the need for a simple, accessible grade calculator
- Thanks to the Tunisian education system for the standardized grading structure

## 📧 Contact & Support

Have questions or suggestions? Feel free to:
- Open an issue
- Submit a pull request
- Contact me directly

---

**Made with ❤️ in Tunisia 🇹🇳**

⭐ Star this repo if you find it helpful!
