# Academico
Academico is a smart, interactive study app designed to make learning easier, faster, and more personal. It instantly creates custom quizzes, practice tests, and clear explanations for any topic — helping students actually understand what they’re learning instead of just memorizing it.

---

## ✨ Overview

Many students waste time searching for good study materials or trying to create their own. Academico fixes that by giving learners a simple, focused tool that can generate practice questions, explanations, and quick reviews on the spot.

Students type in any topic, and the app instantly:

* Creates custom quizzes and practice tests
* Generates clear explanations
* Helps students review, test themselves, and understand concepts more deeply

Academico keeps studying efficient, organized, and distraction-free.

---

## ⚙️ App Architecture

```
src/
├── main.dart                   → App entry point
├── screens/
│   ├── home_screen.dart        → Main UI and topic input
│   ├── quiz_screen.dart        → Generated quizzes and feedback
│   └── review_screen.dart      → Explanations and learning content
├── widgets/
│   ├── question_card.dart      → Quiz question UI
│   └── result_summary.dart     → Score + explanation summary
├── services/
│   ├── generator.dart          → Quiz + explanation generation logic
│   └── local_storage.dart      → Offline data storage
├── theme/
│   └── app_theme.dart          → Centralized styling
└── utils/
    └── formats.dart            → Helpers for formatting questions & results
```

---

## 🧠 How It Works

### Input → Generate → Learn

1. **Student enters a topic** (ex: “Photosynthesis”, “Algebra linear equations”).
2. **Academico generates**:

   * Multiple-choice questions
   * Short-answer prompts
   * Quick explanations
3. **Students practice** in quiz mode or explanation mode.
4. **All data stays local**, so the app works offline.

### Under the Hood

* **Frontend:** Flutter (Dart)
* **Local Storage:** SharedPreferences / Hive
* **State Management:** Provider
* **Generation Engine:** Rule‑based + structured templates for fast, offline quiz creation

---

## 💡 Key Features

* Instant quiz + explanation generation for any topic
* Offline functionality—no external APIs required
* Clean, distraction-free interface
* Support for multiple question types
* Progress feedback after each quiz
* Consistent UI theme for easy reading

---

## 🚀 Future Plans (v2.0 Ideas)

* Personalized learning tracking and adaptive quiz difficulty
* Voice-assisted learning and spoken explanations
* Gamification: badges, streaks, study goals
* Expanded subject coverage across grade levels
* Smarter explanations that adapt to a student’s learning style

---

## 📦 Installation

```
flutter pub get
flutter run
```

---

## 🖼️ Preview

*(Add screenshots or logo here)*

---

## 📄 License

MIT License
