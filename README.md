# GitHub Contributions Plot Analytics

Interactive webapp to visualize GitHub contribution history in multiple chart views: daily timeline, monthly bars, cumulative growth, and weekday breakdown.

## Features

- **Daily Line Plot** — Continuous timeline of daily contributions
- **Monthly Bar Chart** — Aggregated monthly volume
- **Cumulative Growth** — Running total over time
- **Weekday Distribution** — Activity breakdown by day of week
- **Dark/Light mode** — Auto-detects system preference, manual toggle
- **Real GitHub data** — Fetches from GitHub API via public proxy
- **Demo fallback** — Works offline with realistic sample data

## Live Demo

https://kassoulet.github.io/contributions-plot

## Quick Start

Open `index.html` directly in a browser, or serve locally:

```bash
npx serve .
# or
python3 -m http.server
```

## Tech Stack

- Vanilla HTML/CSS/JS (single file, no build step)
- [Chart.js](https://www.chartjs.org/) for rendering
- [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Lucide Icons](https://lucide.dev/)
- GitHub Contributions API proxy by [jogruber](https://github.com/jogruber/github-contributions-api)

## License

MIT
