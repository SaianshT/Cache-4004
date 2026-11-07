# Cache-4004

> **Zero-latency recall for competitive quizzers.**

Built for participants of competitive Science and Technology Quizzes (TCS InQuizitive, ShriTeq, and school circuits). This is a zero-dependency study platform — no frameworks, no build steps, no install. Just open `index.html` and commit tech lore to instant recall.

---

## ✨ Features

| Feature | Description |
|---|---|
|**Knowledge Base** | Detailed reference tables covering IT companies, acronyms, tech media, and more |
|**Practice Quizzes** | 1000+ Q&A pairs filterable by category and difficulty |
|**Flashcard Mode** | Flip-card study session with a shuffled deck (Fisher-Yates algorithm - no repeats!) |
|**List View Mode** | Paginated Q&A list with reveal-on-click answers |
|**Strategy Guide** | Quizzing strategy and insights|
|**External Resources** | Curated archive of external resources for additional exposure|

---

## 🚀 Getting Started

No installation required. This is a pure HTML/CSS/JS app.
Hosted currently on GitHub pages: https://saiansht.github.io/Cache-4004/ 
---

## 📊 Quiz Database

**1000 questions** across 17 categories and 3 difficulty levels.

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
- **Indian Startups & Tech**
- **Codenames** — Windows OS, Android OS, Intel Processors, Apple macOS
- **Acronyms** — IT Infrastructure, Gaming Terminology, Corporate Etymology
- **Books by Tech Personalities**
- **Tech-Based Media** — Movies, Sci-Fi Books, Web Series

---

## 🗂️ Project Structure

```
Cache-4004/
├── index.html          # SPA shell — all views, toggled via CSS
├── app.js              # All logic: routing, KB, quiz engine, flashcards
├── style.css           # Hand-crafted design system
├── knowledgebase.json  # Reference data
└── quiz.json           # 1000 Q&A pairs
```

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

This project is open-source. Feel free to use, adapt, and share it - credit is always appreciated!

---

<div align="center">
  Made by <strong>Saiansh Tapuriah</strong>
</div>
