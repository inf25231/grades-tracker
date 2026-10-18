# Grade Tracker

Simple, clean dashboard for tracking university exams, modules, ECTS credits, and grades. Easily adaptable to any curriculum.

## Features

- **Exams schedule**: Chronological list of exams with dates, times, assessment formats, and grades.
- **Module overview**: Grouped by semester with ECTS credit tally, expandable sub-courses, and weighted grades.
- **Grade colors**: Color-coded badges based on the German grade scale (1.0 to 5.0).
- **Search & filter**: Instant search by subject or module code, plus semester filter tabs.
- **Visual Data Editor**: Built-in web editor (`editor.html`) to manage and export your `data.json` without writing code.
- **Bilingual**: One-click toggle between German (DE) and English (EN).
- **Zero build step**: Pure static HTML, CSS, and JS. No frameworks, no dependencies.

## Local setup

Run any static server:

```bash
python3 -m http.server 8000
```

Open `http://localhost:8000` in your browser.

To track your own grades:
1. Copy `data.example.json` to `data.json`.
2. Add your courses and grades. `data.json` is gitignored so your personal records will never be pushed.

## GitHub Pages

1. In your GitHub repo: **Settings** → **Pages** → Source: **Deploy from a branch** → Branch: `main` / `/ (root)`.
2. The site will be live at `https://inf25231.github.io/grades-tracker/` running on the anonymized sample data.
