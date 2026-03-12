# ⚔️ Term Wars — Algebra Combat

> A browser-based algebra game for Form 1 students (ages 11–13).  
> Built as a single HTML file. No installation. No internet required after download.
> https://legallev-teach.github.io/term-wars/
---

## 🎮 What It Is

Term Wars is a three-stage game that teaches students to identify, classify, and simplify algebraic terms. It was designed for use in a Caribbean secondary school context, aligned with the CSEC mathematics preparation curriculum.

Students fight through three progressively harder stages, earning points, triggering boss rounds, and generating a submission code at the end so their teacher can verify their score.

---

## 🕹️ How to Play

1. Download `term-wars.html`
2. Open it in any modern browser — Chrome, Firefox, Edge, or Safari
3. Enter your name and tap **START GAME**
4. Complete all three stages to get your submission code
5. Screenshot the final screen and submit to your teacher

No login. No account. No data leaves your device.

---

## 📚 The Three Stages

### Stage 1 — Term Sorter
Drag or tap algebraic terms into the correct buckets (x-terms, y-terms, constants, etc.). Introduces vocabulary: term, variable, coefficient, constant, like terms.

**Boss Rounds:** Find the wrongly-placed term — sometimes there are two mistakes.

### Stage 2 — Coefficient Spotter
A term is displayed on screen. Identify its coefficient, variable, or exponent from multiple choice options. Covers negative coefficients, hidden exponents of 1, the zero exponent rule, and the difference between coefficient and variable.

**Boss Rounds:** A fictional student has labelled a term incorrectly. Find the wrong label.

### Stage 3 — Simplify Race
Type the simplified form of an expression using the on-screen keypad. Fights three common misconceptions:

| War | Mistake | Example |
|-----|---------|---------|
| War 1 | Adding grows the exponent | `3x + 5x = 8x²` ❌ |
| War 2 | Unlike terms can combine | `7x + 2 = 9x` ❌ |
| War 3 | Variable disappears | `4x + 3x = 7` ❌ |

**Boss Rounds:** A worked solution has one wrong step. Find it.

---

## 🏆 Scoring

| Source | Points |
|--------|--------|
| Correct answer | +10–15 |
| Time bonus (fast answers) | +2–5 |
| Boss round correct | +10–20 |
| Wrong attempt | −2 to −5 |

Scores can exceed the base maximum due to time and boss bonuses — this is intentional. The final screen shows a **band rating**:

| Band | Score | Label |
|------|-------|-------|
| A | 280+ | Excellent |
| B | 210–279 | Good |
| C | 140–209 | Pass |
| D | Below 140 | Keep Practising |

---

## 👩‍🏫 Teacher Features

Enter the teacher code on the title screen to access the **Teacher Dashboard**:

```
6622241
```

### Unlock Codes (give to students as needed)

| Code | Effect |
|------|--------|
| `SKIP1` | Unlock Stage 2 directly |
| `SKIP2` | Unlock Stage 3 directly |
| `SKIPALL` | Unlock all stages |
| `FREEPLAY` | Remove all unlock gates (stages accessible regardless of score) |
| `REVIEW` | Show all teaching popups |

### Score Decoder

Students submit a code like `TW-0L1F-1324`. Paste it into the Teacher Dashboard to reveal:

- True score
- Stage-by-stage breakdown
- Challenge attempt count
- Band (A/B/C/D)

### Submission Workflow

1. Students complete all three stages
2. Final screen displays: **name + total score + submission code**
3. Students screenshot the screen
4. Screenshot is submitted to the teacher (WhatsApp, Schoology, printed, etc.)
5. Teacher decodes the code to verify the score

---

## 💾 Save & Resume

Progress is saved automatically to the browser's local storage after each stage is completed. If a student refreshes or closes the tab mid-game, they can resume from where they left off.

- A **RESUME** button appears on the title screen if a save is detected
- **CLEAR SAVE** wipes the saved data so a new student can start fresh
- Save is automatically cleared when a student reaches the final screen

> **Note:** Save data is stored per browser. If a student switches devices, they start over.

---

## 🔊 Sound

The game uses the Web Audio API to generate synthesised sounds — no audio files, no extra download size. All sounds are created in-browser.

A **🔊 mute button** sits in the bottom-right corner. Mute preference is saved across sessions.

Works on Chrome, Firefox, Edge, and Safari (including iOS Safari).

---

## 📱 Device Compatibility

| Device | Support |
|--------|---------|
| Desktop (Chrome, Firefox, Edge) | ✅ Full |
| Desktop Safari | ✅ Full |
| Android (Chrome) | ✅ Full |
| iPhone / iPad (Safari) | ✅ Full |
| Offline (after first load) | ✅ Full |

The game is touch-friendly. Drag-and-drop in Stage 1 works via tap-to-select on mobile.

---

## 🗂️ File Structure

```
term-wars.html    ← The entire game. This is the only file needed.
README.md         ← This file
```

Everything — HTML, CSS, JavaScript, embedded fonts — is contained in a single `.html` file. Share it via WhatsApp, Google Drive, Schoology, USB, or GitHub Pages.

---

## 🚀 Hosting on GitHub Pages

1. Upload `term-wars.html` to a GitHub repository
2. Go to **Settings → Pages**
3. Set source to your main branch, root folder
4. Your game will be live at `https://yourusername.github.io/repo-name/term-wars.html`

Students can open the link and play directly in their browser with no download required.

---

## 🛠️ Technical Notes

- Pure HTML/CSS/JavaScript — no frameworks, no dependencies
- Web Audio API for sound (synthesised, no audio files)
- localStorage for save data (fails silently if unavailable)
- Single file, ~196 KB
- Works fully offline after the first page load
- Fonts load from Google Fonts with embedded fallbacks for offline use

---

## 📋 Curriculum Alignment

Designed for **Form 1 Mathematics** in the Trinidad and Tobago secondary school system, covering:

- Algebraic terminology (term, variable, coefficient, constant, exponent)
- Classification of terms (like vs unlike)
- Simplification of algebraic expressions
- Common misconceptions targeted explicitly (Wars 1, 2, and 3)

---

## 👤 Author

Developed by E. A. Legall, a Form 1 Mathematics teacher at Caribbean Union College Secondary School, St. Joseph, Trinidad and Tobago.

Built with the assistance of Claude (Anthropic) over multiple iterative sessions.

---

## 📄 Licence

This project is free to use for educational purposes.  
Please do not redistribute for commercial gain.
