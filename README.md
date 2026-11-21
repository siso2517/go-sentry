# go-sentry

![License](https://img.shields.io/github/license/siso2517/go-sentry?color=blue) ![HTML](https://img.shields.io/badge/html-5-E34F26) ![No Build](https://img.shields.io/badge/no%20build-required-success)

go-sentry is a fast, accessible static landing page with CSS variables for theming, lazy-loaded feature cards with IntersectionObserver animations, smooth-scroll anchor navigation, and a hand-crafted SVG favicon. Built with semantic HTML, ARIA labels, and keyboard-navigable navigation. No build step -- just open index.html in a browser.

## Features

- Semantic HTML with ARIA labels and keyboard-navigable navigation
- Smooth-scroll navigation with IntersectionObserver
- Fully responsive design with CSS Grid and Flexbox
- Under 10KB gzipped -- no frameworks, no dependencies
- No build step required -- just open index.html in a browser
- CSS custom properties for easy theme customization (--primary, --text, --bg)
- Feature cards with scroll-triggered fade-in animations

## Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, Edge)
- Optional: Python 3 for local serving

## Installation

```bash
git clone https://github.com/siso2517/go-sentry.git
cd go-sentry
# open index.html in your browser
# or serve locally
python3 -m http.server 8000
```

## Usage

```bash
# Just open index.html in a browser
open index.html

# Or serve locally with Python
python3 -m http.server 8000
# Visit http://localhost:8000

# The site includes:
# - A hero section with a call-to-action button
# - A responsive feature grid with 3 cards
# - Smooth-scroll navigation
# - Scroll-triggered fade-in animations on feature cards
```

## Project Structure

```
go-sentry/
├── index.html
├── styles.css  script.js  favicon.svg
├── README.md  LICENSE  CHANGELOG.md  CONTRIBUTING.md  CODE_OF_CONDUCT.md
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   ├── bug_report.md
│   │   └── feature_request.md
│   └── PULL_REQUEST_TEMPLATE.md
└── .gitignore
```

## Running Tests

No automated test suite. To verify manually:

1. Open `index.html` in a browser
2. Check that the hero section renders
3. Click navigation links -- they should smooth-scroll
4. Scroll down -- feature cards should fade in
5. Resize the window -- layout should be responsive

## Contributing

Contributions are welcome! Please read [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

Quick start:

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/my-feature`
3. Make your changes and run tests (see [Running Tests](#running-tests) above)
4. Commit with a clear message: `git commit -am 'Add: my feature'`
5. Push to your fork: `git push origin feature/my-feature`
6. Open a Pull Request

Please ensure all tests pass before submitting a pull request.

## Changelog

See [CHANGELOG.md](CHANGELOG.md) for a list of changes and version history.

## License

This project is licensed under the MIT -- see the [LICENSE](LICENSE) file for details.

Copyright (c) 2026 nina khan.
