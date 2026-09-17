# Philosophy Quest: Lessons 1–5 Summative Review

An interactive Grade 12 review and summative assessment for **Introduction to the Philosophy of the Human Person**. It covers Lessons 1–5 through *Limitations and Transcendence*.

The website is self-contained: its design, question bank, scoring, adaptive second attempt, progress saving, and printable certificate are all inside `index.html`. No installation, framework, account, database, or build step is required.

## Assessment structure

- Guided review of essential concepts before the test
- 25 randomized multiple-choice questions (25 points)
- 2 automatically scored constructed-response questions (5 points each)
- 35 total points
- Adaptive second attempt based on the learner's first score
- Start and completion timestamps
- Responsive layout for Windows, macOS, iPhone, iPad, Android, and modern browsers
- Printable/downloadable certificate of completion

## Project files

| File | Purpose |
|---|---|
| `index.html` | The complete website and assessment |
| `README.md` | Project overview and quick-start instructions |
| `DEPLOYMENT.md` | GitHub Pages publishing instructions |
| `TEACHER_GUIDE.md` | Classroom use, scoring, and customization notes |
| `PRIVACY.md` | Student-data and browser-storage information |
| `.nojekyll` | Tells GitHub Pages to serve the project as a plain static site |

## Run locally

The simplest method is to double-click `index.html` and open it in a current browser.

For a local web-server preview, open a terminal in this folder and run:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Publish

See [DEPLOYMENT.md](DEPLOYMENT.md) for browser-based and command-line GitHub Pages instructions.

## Important classroom limitations

- Scoring happens entirely in the student's browser. There is no central gradebook or submission server.
- Progress is stored only in that browser and device. Private/incognito browsing, clearing site data, or switching devices can remove or hide saved progress.
- Because this is a static client-side website, answer keys and scoring logic are visible to technically knowledgeable users. It is best used as a summative review or teacher-supervised assessment, not as a secure high-stakes exam.
- Automatic essay scoring checks required concepts and response quality heuristically. A teacher should review constructed responses when scores will become official grades.
- GitHub Pages sites are public unless access is controlled through an eligible GitHub plan and configuration.

## Customization

Open `index.html` in a code editor. The review content, question bank, rubrics, colors, and interface logic are embedded in that one file. Keep a backup before changing question IDs, scoring rules, or saved-data keys.

## License

No open-source license is included. The owner retains the applicable rights to the teaching materials and should choose a license before permitting public reuse or modification.
