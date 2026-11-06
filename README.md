# 🧠 Tech Quiz Mastery Library

> **An open-source tech trivia database and interactive study platform for competitive quizzers.**

Built for participants of events like **TCS InQuizitive** and **ShriTeq**, this is a fully self-contained study tool — no frameworks, no build steps, no install. Just open `index.html` and go.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📚 **Knowledge Base** | Structured reference tables covering IT companies, OS codenames, acronyms, tech media, and more |
| 💡 **Practice Quizzes** | 1,000 curated Q&A pairs filterable by category and difficulty |
| 🃏 **Flashcard Mode** | Flip-card study session with a shuffled deck (Fisher-Yates algorithm — no repeats!) |
| 📋 **List View Mode** | Paginated Q&A list with reveal-on-click answers |
| 🧠 **Strategy Guide** | Round-format cheat sheets for grid-based rounds like *All or Nothing* |
| 🔗 **External Resources** | Curated archive of TCS InQuizitive (2022–2025) and ShriTeq (2023–2025) livestreams |

---

## 🚀 Getting Started

No installation required. This is a pure HTML/CSS/JS app.

```bash
# Clone the repository
git clone https://github.com/SaianshT/tech-quiz-resources.git

# Open in your browser
open index.html   # macOS
start index.html  # Windows
```

> **Note:** The app fetches `knowledgebase.json` and `quiz.json` via `fetch()`. If you're opening the file directly (via `file://`), you may need to serve it through a local server due to browser CORS restrictions.

```bash
# Quick local server (Python)
python -m http.server 8000
# Then visit http://localhost:8000
```

---

## 📊 Quiz Database

**1,000 questions** across 17 categories and 3 difficulty levels.

### By Category

| Category | Questions |
|---|---|
| Software | 144 |
| Video Games | 79 |
| IT Companies | 76 |
| Programming | 65 |
| Tech Personalities | 60 |
| Movies | 57 |
| Emerging Tech | 57 |
| Cybersecurity | 56 |
| Acronyms | 107 |
| Hardware | 107 |
| Tech History | 38 |
| Space Tech | 33 |
| India Tech | 29 |
| Sports Tech | 28 |
| Crypto | 23 |
| Books | 22 |
| Robotics | 19 |

### By Difficulty

| Difficulty | Questions |
|---|---|
| 🟢 Easy | 312 |
| 🟡 Medium | 446 |
| 🔴 Hard | 242 |

---

## 📚 Knowledge Base Categories

The structured reference database covers:

- **Major IT Companies & Lore** — Founders, CEOs, HQs, acquisitions, taglines
- **Indian Startups Ecosystem**
- **Codenames** — Windows OS, Android OS, Intel Processors, Apple macOS
- **Acronyms** — IT Infrastructure, Gaming Terminology, Corporate Etymology
- **Books by Tech Personalities**
- **Tech-Based Media** — Movies, Sci-Fi Books, Web Series

---

## 🗂️ Project Structure

```
tech-quiz-resources/
├── index.html          # SPA shell — all views, toggled via CSS
├── app.js              # All logic: routing, KB, quiz engine, flashcards
├── style.css           # Full hand-crafted design system
├── knowledgebase.json  # Structured reference data
└── quiz.json           # 1,000 Q&A pairs
```

---

## 🏆 External Resources Included

### TCS InQuizitive Archive
Regional and National Finals broadcasts from **2022 to 2025** across cities including Bangalore, Chennai, Delhi, Mumbai, Hyderabad, Pune, Ahmedabad, Kochi, Kolkata, Nagpur, Indore, and Bhubaneswar.

### ShriTeq Livestreams
Middle and Senior school broadcasts from **2023 to 2025** — Finals and Semifinals.

---

## 🛠️ Tech Stack

- **HTML5** — Semantic markup, single-page architecture
- **CSS3** — Custom properties, animations, responsive grid
- **Vanilla JavaScript (ES6+)** — Zero dependencies, zero build tooling
- **JSON** — All data stored in flat, human-readable files

---

## 🤝 Contributing

Contributions are welcome! If you'd like to add questions, fix answers, or expand the knowledge base:

1. Fork the repo
2. Add/edit entries in `quiz.json` or `knowledgebase.json`
3. Follow the existing JSON schema for each category
4. Open a pull request with a short description of what you changed

**Quiz entry format:**
```json
{
  "id": 1001,
  "category": "software",
  "difficulty": "medium",
  "question": "Your question here?",
  "answer": "Your answer here"
}
```

---

## 📄 License

This project is open-source. Feel free to use, adapt, and share it — a credit is always appreciated!

---

<div align="center">
  Made with ☕ by <strong>Saiansh Tapuriah</strong>
</div>
