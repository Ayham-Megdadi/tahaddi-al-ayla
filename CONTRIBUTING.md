# Contributing to تحدّي العيلة

Thank you for your interest! Contributions are welcome — especially new questions and bug fixes.

---

## Ways to Contribute

| Type | How |
|------|-----|
| 🐛 **Bug report** | Open an Issue with steps to reproduce |
| 💡 **Feature idea** | Open an Issue with `[Feature]` in the title |
| 📝 **New questions** | Submit a JSON file via Pull Request (see format below) |
| 🌍 **Translation** | Open an Issue to discuss adding a new language |
| 🎨 **UI improvement** | Open an Issue first to align on the change |

---

## Adding Questions (Most Welcome!)

The best contribution you can make is new high-quality Arabic survey questions.

### Question JSON Format

```json
[
  {
    "q": "شو أكثر شي بتشتريه الناس أون لاين؟",
    "cat": "تسوق",
    "diff": "سهل",
    "a": [
      ["ملابس", 38, ["ثياب", "لبس"]],
      ["إلكترونيات", 27, ["موبايل", "أجهزة"]],
      ["طعام", 18, ["أكل", "طلبات"]],
      ["كتب", 10, ["روايات"]],
      ["مستحضرات", 7, ["عطور", "كريمات"]]
    ]
  }
]
```

**Format:** `["Answer text", points, ["synonym1", "synonym2"]]`

### Question Quality Guidelines

- Questions should reflect **what people commonly answer** — not what is technically correct
- Each question should have **4–8 answers** with points summing to ~100
- Synonyms should cover common **dialect variations** (شامي، خليجي، مصري)
- Avoid questions with sensitive, political, or divisive content
- Test your questions with `restoreOriginalBank()` to make sure they import correctly

---

## Code Contributions

Since this is a single-file project, keep changes minimal and focused:

1. Fork the repository
2. Create a branch: `git checkout -b fix/your-fix-name`
3. Make your changes in `index.html`
4. Test in at least two browsers (Chrome + Firefox)
5. Test on mobile screen size
6. Open a Pull Request with a clear description of what changed and why

### Code Style

- Vanilla JS only — no frameworks, no npm, no build step
- Keep the single-file structure — do not split into multiple files
- Maintain full RTL support — test all UI changes in Arabic
- CSS variables are in `:root` — use them, don't hardcode colors
- `localStorage` keys: `tahaddi_questions`, `tahaddi_state`

---

## What Will NOT Be Merged

- Breaking the single-file structure
- Adding external dependencies or CDN scripts (beyond the Google Fonts already used)
- Removing RTL/Arabic support
- Questions with political, religious, or offensive content

---

*شكراً على مساهمتك — Ayham Megdadi*
