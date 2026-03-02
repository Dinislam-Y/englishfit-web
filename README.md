# EnglishFit — English Grammar Trainer

Interactive English grammar trainer. Not a textbook — a workout for your English. Build sentences from words, choose the right answer in seconds, and train your listening skills.

## Download

[**Android (RuStore)**](https://www.rustore.ru/catalog/app/com.d6apps.englishfit)

## Web Demo

[**Open EnglishFit**](https://dinislam-y.github.io/phrase-gym-web/)

Click **"Continue as Guest"** to try the app without registration.

## What's Inside

- **195 lessons** across 5 levels (A1–C1)
- **3 training modes:** Sentence Assembly, Binary Choice, Listening
- **1000+ voiced words** with native pronunciation
- **Spaced repetition** — the app tracks your mistakes and brings them back
- **Vocabulary quiz** — learn new words with flashcard drills
- **Theory & Quizzes** — grammar rules with comprehension tests
- **Progress tracking** — achievements, streaks, and detailed stats
- **Fully offline**, no ads

## Features

- **Sentence Assembly** — build correct sentences from word chips with instant feedback
- **Listening Exercises** — listen and transcribe audio, improving comprehension skills
- **Binary Choice** — choose between commonly confused words (e.g., *make* vs *do*)
- **Vocabulary Builder** — learn new words with spaced repetition
- **Theory & Quizzes** — read grammar rules and test your understanding
- **Progress Tracking** — achievements, streaks, and detailed statistics

## Tech Stack

- **Flutter** (Dart) — cross-platform UI framework
- **flutter_bloc** (Cubit) — state management
- **GoRouter** — declarative routing
- **Firebase** — authentication and cloud sync
- **Clean Architecture** — Presentation / Domain / Data layers
- **GetIt + Injectable** — dependency injection
- **Freezed** — immutable data classes

## Architecture

```
lib/
  core/        # App-wide: router, theme, services, DI
  shared/      # Reusable widgets and cross-feature services
  features/
    auth/      # Authentication (email + guest mode)
    home/      # Home screen with lesson categories
    lesson/    # Sentence assembly exercises
    listening/ # Audio comprehension exercises
    binary_choice/ # A/B word choice training
    vocabulary/    # Vocabulary building
    theory/    # Grammar theory + quizzes
    profile/   # User profile and settings
    achievements/ # Gamification system
    subscription/  # In-app purchases (RuStore / Google Play / StoreKit)
```

## Screenshots

| Home | Lesson | Listening |
|------|--------|-----------|
| Categorized grammar lessons | Drag-and-drop sentence building | Audio transcription exercises |

## Author

**Dinislam Yakupov** — Flutter Developer

## Links

- [RuStore](https://www.rustore.ru/catalog/app/com.d6apps.englishfit)
- [Privacy Policy](https://dinislam-y.github.io/englishfit-legal/)
- [Support](mailto:englishfit.app@mail.ru)

## License

This is a demo deployment for portfolio purposes.
