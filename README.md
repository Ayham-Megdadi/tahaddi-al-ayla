<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Tajawal&size=32&pause=1000&color=F6C453&center=true&vCenter=true&width=800&lines=%D8%AA%D8%AD%D8%AF%D9%91%D9%8A+%D8%A7%D9%84%D8%B9%D9%8A%D9%84%D8%A9;%D9%85%D9%8A%D9%86+%D8%A8%D8%B9%D8%B1%D9%81+%D8%A7%D9%84%D9%86%D8%A7%D8%B3+%D8%A3%D9%83%D8%AB%D8%B1%D8%9F;Arabic+Family+Feud+%E2%80%94+Browser+Game" alt="Typing SVG" />

<br/><br/>

![HTML](https://img.shields.io/badge/HTML5-Single%20File-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-Custom%20Design-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JS](https://img.shields.io/badge/JavaScript-Vanilla-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Arabic](https://img.shields.io/badge/Language-Arabic%20RTL-green?style=for-the-badge)
![Offline](https://img.shields.io/badge/Works-100%25%20Offline-brightgreen?style=for-the-badge)
![Dependencies](https://img.shields.io/badge/Dependencies-Zero-orange?style=for-the-badge)

<br/>

> **Developed by [Ayham Megdadi](https://www.instagram.com/ayham_megdadi/)**  
> Arabic Family Feud-style browser game — no server, no install, just open and play.

</div>

---

## 📖 Overview

**تحدّي العيلة** is a fully interactive Arabic **Family Feud-style quiz game** that runs entirely in the browser — no server, no internet connection, no installation required.

Designed for Arabic-speaking families and groups, it brings the excitement of TV game shows to any device. The host presents survey questions, teams guess the most popular answers, and points are tracked automatically — all within a single self-contained HTML file.

---

## 🎮 Live Demo

**[🕹️ Play Now →](https://ayham-megdadi.github.io/tahaddi-al-ayla)**

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎯 **Smart Answer Matching** | Accepts synonyms, dialects, and minor spelling mistakes without being too lenient |
| 🔄 **Steal Mechanic** | Full steal round — opposing team gets one chance when the main team hits max strikes |
| ⚡ **Fast Money Round** | Final tiebreaker — two players answer 5 questions each against a 30s timer, goal: 200 points |
| 🏆 **Score Multiplier** | Advanced rounds can multiply points (×1 to ×5) |
| ⏱️ **Optional Timer** | Configurable countdown per round (10–300 seconds) |
| 📝 **Host Control Panel** | Manual reveal, wrong answer, undo, switch turn, steal success/fail, ±10 point adjustment |
| 📚 **Question Bank** | Built-in bank with categories and difficulty levels (سهل / متوسط / صعب) |
| ➕ **Custom Questions** | Add, edit, and delete questions with custom answers, points, and synonyms |
| 📤 **Import / Export** | Export bank as JSON — import custom question sets |
| 💾 **Auto-Save** | Game state saved to `localStorage` — resume any time |
| 🔊 **Sound Effects** | Toggleable audio feedback for correct answers, errors, and win |
| 🌙 **Dark UI** | Navy + gold design — easy on the eyes in any lighting |
| 📱 **Responsive** | Works on desktop, tablet, and mobile |
| 🌐 **Full RTL** | 100% Arabic right-to-left layout throughout |
| 🚫 **Zero Dependencies** | Pure HTML + CSS + JavaScript — single file, no frameworks |

---

## 🕹️ How to Play

### Setup
1. Choose team names and colors
2. Set number of rounds, max strikes, point multiplier, category, and difficulty
3. Optionally enable timer and sound

### Gameplay
1. Host reads the question aloud
2. The active team types their answer — correct answers reveal and add points to the round pot
3. Wrong answers add a ❌ strike
4. After reaching max strikes → **Steal Round** — the opposing team gets one guess
   - ✅ Steal succeeds → opposing team takes the full pot
   - ❌ Steal fails → pot stays with the original team
5. Host can manually reveal answers, adjust scores, undo, or skip

### Fast Money (Final Round)
- Player 1 answers 5 questions in 30 seconds
- Player 2 answers the same 5 questions in 30 seconds
- Combined score ≥ 200 → **WIN** 🎉

---

## 📚 Question Bank Format

When adding questions manually or importing via JSON:

```
Answer text | Points | synonym1, synonym2, synonym3
```

**Example:**
```
السؤال: شو أكثر شي يتأخر فيه الناس؟

اجتماعات العمل | 40 | شغل, مواعيد
الحفلات | 28 | أفراح, سهرات
الدكتور | 15 | طبيب, مستشفى
```

---

## 🚀 Quick Start

```bash
# No install needed — just download and open
git clone https://github.com/Ayham-Megdadi/tahaddi-aleila.git
cd tahaddi-aleila
open index.html
# or just double-click index.html
```

Or use the **[Live Demo](https://ayham-megdadi.github.io/tahaddi-al-ayla/)** directly.

---

## 🗂️ Repository Structure

```
tahaddi-aleila/
├── index.html          ← Complete game — single self-contained file
├── Tahaddi_ayham.png   ← OG image / favicon
└── README.md
```

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 — custom variables, animations, RTL |
| Logic | Vanilla JavaScript — no frameworks |
| Storage | `localStorage` — auto-save & resume |
| Font | Cairo + Tajawal (Google Fonts CDN) |
| Distribution | Single `.html` file |

---

## ⚖️ License

This project is open source under the **MIT License** — free to use, share, and modify with attribution.

---

<div align="center">

*Built with ❤️ by [Ayham Megdadi](https://www.instagram.com/ayham_megdadi/)*  
*⭐ Star this repo if your family enjoyed the game!*

</div>
