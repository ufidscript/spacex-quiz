# SpaceX Quiz

![license](https://img.shields.io/badge/license-MIT-green)

Small quiz web app created during Dev Day Minna together with session participants while exploring the GitHub Copilot app.

## Summary

- A lightweight single-page quiz built with plain HTML, CSS and JavaScript.
- Single file app: [index.html](C:/projects/spaceX-quiz/index.html)

## Features

- Multiple-choice quiz flow
- Score tracking and simple feedback
- No build step — works offline in any modern browser

## Screenshot

Add a screenshot to the repo (e.g. `screenshots/quiz.png`) and update this section to show it:

![screenshot](./screenshots/quiz.png)

## Run locally

1. Open `index.html` directly in your browser.

2. Serve with a simple static server (recommended for consistent behavior):

   - npm: `npx serve .` (open http://localhost:5000)
   - Python 3: `python -m http.server 8000` (open http://localhost:8000)
   - VS Code: install the "Live Server" extension and choose "Open with Live Server"

## Usage

- Start the quiz and answer the multiple-choice questions.
- At the end you'll see a score and basic feedback.
- To change questions, edit the `index.html` file — the questions are embedded in the script.

## Development

Suggested small improvements you can add:

- Move questions to a JSON file and load them dynamically
- Add unit / integration tests (Jest, Playwright)
- Add CI (GitHub Actions) to run linters and tests
- Improve accessibility (keyboard navigation, ARIA labels)

## Contributing

Contributions welcome. Please:

1. Fork the repo
2. Create a branch for your change
3. Open a pull request with a clear description of the change

If you want help turning this into a published project (GitHub repo, npm pages, CI), open an issue and I can help.

## License

This project is licensed under the MIT License — see the [LICENSE](C:/projects/spaceX-quiz/LICENSE) file. Replace the author/year in the LICENSE file with your own before publishing.

---

This project was created during a live Dev Day session to introduce attendees to the power of the github copilot appand is intended for open-sourcing.
