# 🧠 Tech Quiz Mastery Library

> **An open-source tech trivia database and interactive study platform for competitive quizzers.**

Built for participants of Science and Technology Quizzes, this is a fully self-contained study tool - no frameworks, no build steps, no install. Just open `index.html` and explore.

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
Hosted currently on GitHub pages: https://saiansht.github.io/tech-quiz-resources/ 
---

## 📊 Quiz Database

**1000 questions** across 17 categories and 3 difficulty levels.

### Current Category List

|---|
| Software |
| Video Games |
| IT Companies |
| Programming |
| Tech Personalities |
| Movies |
| Emerging Tech |
| Cybersecurity |
| Acronyms |
| Hardware |
| Tech History |
| Space Tech |
| India Tech |
| Sports Tech |
| Crypto |
| Books |
| Robotics |

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
tech-quiz-resources/
├── index.html          # SPA shell — all views, toggled via CSS
├── app.js              # All logic: routing, KB, quiz engine, flashcards
├── style.css           # Hand-crafted design system
├── knowledgebase.json  # Reference data
└── quiz.json           # 1000 Q&A pairs
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

This project is open-source. Feel free to use, adapt, and share it - credit is always appreciated!

---

<div align="center">
  Made by <strong>Saiansh Tapuriah</strong>
</div>
