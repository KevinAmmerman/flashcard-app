# Flashcard App

A feature-rich flashcard application built as a Frontend Mentor challenge. This app helps users create, manage, and study flashcards with a comprehensive mastery tracking system.

## Features

### Flashcard Management
- Create, edit, and delete flashcards with questions, answers, and categories
- Form validation for required fields
- Grid layout view of all flashcards
- Toast notifications for CRUD operations

### Study Mode
- Study flashcards one at a time
- Click to reveal answers with flip animation
- Track mastery progress (0-5 scale)
- Navigate between cards with Previous/Next buttons
- Card counter display (e.g., "Card 1 of 40")
- Reset progress option

### Filtering & Organization
- Multi-category filter selection
- Card count per category
- Hide mastered cards option
- Shuffle functionality for randomized study

### Statistics & Progress
- Total cards counter
- Mastered cards (knownCount = 5)
- In progress cards (knownCount = 1-4)
- Not started cards (knownCount = 0)

### UI Features
- Responsive design for all device sizes
- Keyboard navigation support
- Hover and focus states
- Load more functionality (12 cards per batch)
- Accessible modal interactions

## Tech Stack

- React + TypeScript
- Vite
- LocalStorage for data persistence

## Data Model

Each flashcard has the following structure:

```json
{
  "id": "fc001",
  "question": "What does HTML stand for?",
  "answer": "HyperText Markup Language",
  "category": "Web Development",
  "knownCount": 0
}
```

## Getting Started

1. Clone the repository
```bash
git clone <repository-url>
```

2. Install dependencies
```bash
npm install
```

3. Start development server
```bash
npm run dev
```

## Building for Production

```bash
npm run build
```

## Challenge

This is a premium [Frontend Mentor](https://www.frontendmentor.io) challenge focused on building a complete flashcard learning application with advanced features like mastery tracking, filtering, and data persistence.

**Skills required:** Strong understanding of HTML, CSS, and JavaScript/TypeScript
