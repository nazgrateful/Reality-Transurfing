# Reality-Transurfing

**Transurfing Path** (`index.html`) is a single-file study app for three books. Switch between them with the buttons at the top.

## Reality Transurfing (Vadim Zeland)
- **Lessons**: the 78-day course on top (one principle a day from *Transurfing in 78 Days*, with a summary, practice, notes and one-a-day pacing), then 18 core lessons that go deeper, each with key ideas, an exercise, a quiz and a reflection. Days and lessons link to each other.
- **Practice**: eight daily practices with a 16-week heatmap and streak.
- **Glossary**: searchable terms linked to their lessons.
- **Book tracker**: page and chapter in your own copy.

The lessons and 78-day summaries are plain-language study notes written for this app, not the book's text.

## It Works (R. H. Jarrett, 1926)
- **Read**: the complete original text of *It Works* and *The Magic Story* (F. V. R. Dey, 1900), both in the public domain.
- **My List**: write your wants in order of importance, reorder and edit them, tick off the morning, noon and night readings, and mark wants as received with a note of thanks.
- **Lessons**: eight lessons with quizzes, plus practices and a glossary.

## The Master Key System (Charles F. Haanel, 1912/1916)
- **Read**: the complete original text (public domain) of all 24 parts, with Haanel's introductory letters and tap-to-reveal study questions.
- **Weeks**: the 24 parts as a week-by-week course, each with a summary, Haanel's sitting exercise for that week, a quiz and a reflection.
- **Today**: current week, a 24-week progress strip, and a 15/20/30-minute sitting timer that logs the day's sitting when it finishes.
- **Practice** and **Glossary** for the book's habits and terms.

The weekly summaries and quizzes are study notes written for this app.

## Shared
- **Calendar**: a month view of everything you practised, read or wrote in each book, with day details.
- **Alarms**: daily times for each practice, set up as real alarms in your phone's Clock app so they ring when the app is closed and through Do Not Disturb (one tap on Android, a copy-and-add checklist on iPhone, with a flag when a phone alarm no longer matches). An in-app alarm and a calendar (`.ics`) export are extras.
- **Journal** and backup, restore and reset cover all books. Everything saves automatically. The streak counts activity in any book.
- Progress is stored in `localStorage` when opened directly in a browser, and privately in your Claude account when opened as a claude.ai artifact.

The look is a 1990s newspaper: newsprint paper, a blackletter masthead with a live dateline (volume, issue, date, section), heavy serif headlines, thick-thin rules and ruled columns, drop caps, small-caps kickers, boxed classified-ad buttons and a printed-listings calendar. Each book is a lettered section with its own spot colour: A blue, B red, C green. Hover effects are optional, under Data → Look.

Open `index.html` in any browser; there is no build step.

## Welcome page (`welcome.html`)
A short, interactive front door to the practice: a live field of life-lines you can touch to choose one, a principle of the day, a pendulum that calms as you lower its importance, a mirror that returns your thought after a delay, and a "slide" maker that turns a want into a present-tense picture (kept in your browser, with a count of days you came back). It ends with a way into the 78-day course in `index.html`.
