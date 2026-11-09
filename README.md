# ⚛️ Physics Quiz — Units, Dimensions & Dimensional Analysis

A focused, single-file quiz that tests first-year university physics: SI units, dimensions, and dimensional analysis. Ten multiple-choice questions with instant feedback, explanations, a final score screen, and a little confetti when you do well.

**Live demo:** https://hoba101.github.io/physics-quiz/

![Physics quiz](docs/screenshot.png)

## ✨ Features

- 10 exam-style questions covering units, dimensional formulae, and equation checking.
- Instant right/wrong feedback with a short explanation after each answer.
- Progress bar, score tracking, and a final grade card.
- Fully responsive, no build step, no dependencies (Font Awesome + Google Fonts via CDN).
- Retry flow to practise again without reloading.

## 🚀 Run locally

Open `index.html` directly in a browser, or serve the folder:

```bash
python3 -m http.server 8080
```

Then visit <http://localhost:8080>.

## 🧠 Topics covered

- SI base units and derived units
- Dimensional formulae
- Dimensional consistency of equations
- Common pitfalls (dimensionally correct ≠ numerically correct)

## 📁 Project structure

```
physics-quiz/
└── index.html   # Markup, styles, questions and quiz logic in one file
```

## 📄 License

[MIT](LICENSE) © 2026 Miro (Ehab)
