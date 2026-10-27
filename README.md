# THINK QUEST 2026–27

THINK QUEST is an offline, browser-based study and quiz application for **Tagisan Ng Talino** competition preparation. It brings subject review, practice questions, timed activities, flashcards, and progress tracking together in a single-page interface.

## Features

- **Dashboard** with study statistics, streaks, and a daily goal.
- **Question Reviewer** with subject and category browsing, search, difficulty filters, explanations, and bookmarks.
- **Quiz Mode** with configurable subject, difficulty, and question count. Questions include multiple-choice, true/false, and short-answer formats.
- **Rapid Fire** for timed recall practice.
- **Mock Exams** with three 50-question practice exams.
- **Flashcards** for active recall, with options to mark cards known or needing review.
- **Bookmarks, mistake review, and progress tracking** to revisit difficult material and monitor results.
- **Dark and light themes**, with responsive layouts for desktop and mobile screens.

The question bank covers Arts and Literature, Social Sciences, Mathematics, Science and Technology, and General Information. An additional set of 50 questions is based on the included PDF handouts and includes source document and page references.

## Getting started

No installation, build step, or server is required:

1. Download or clone this repository.
2. Open `index.html` in a modern web browser.
3. Choose a section from the navigation menu and start reviewing.

The app loads `pdf-quiz.js` and `assets/sti-logo.png` relative to `index.html`, so keep the files and folders in their current locations. For easiest access to the handout files referenced in questions, keep the `Tnt/` folder alongside the application.

## Data and privacy

The app runs in the browser and does not require a backend or send progress to a server. Theme selection, bookmarks, quiz progress, mistakes, and related study state are saved in the browser's `localStorage` on the device. Clearing browser site data, using a different browser or browser profile, or opening the app under a different origin may result in separate or cleared progress. Use the app's reset-progress control to clear saved study progress.

## Project structure

```text
.
├── index.html       # App interface, styles, question bank, and application logic
├── pdf-quiz.js      # Questions based on PDF handouts
├── assets/
│   └── sti-logo.png # Logo used by the interface
└── Tnt/
    ├── *.pdf        # Study handouts referenced by some questions
    └── Diagrams/    # System design and user-guide documents
```

There is no package manager configuration or automated test suite in the repository. The application is implemented with HTML, CSS, and vanilla JavaScript.
