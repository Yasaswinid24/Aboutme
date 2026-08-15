# Yasaswini's Portfolio

A single-page portfolio website showcasing selected AI/ML projects, built to accompany technical interviews and highlight hands-on work in applied machine learning, LLMs, and data pipelines.

**Live site:** [aboutme-1-vfxz.onrender.com](https://aboutme-1-vfxz.onrender.com)

---

## About

This portfolio presents a curated set of projects, each broken down into four sections for clarity and honesty about the engineering process:

- **Problem** – What the project set out to solve
- **Pipeline** – The technical approach and architecture used
- **What Went Wrong** – Challenges, failures, and debugging along the way
- **Result** – Final outcomes and what was learned

The goal is to give reviewers a fast, visual sense of real problem-solving — not just polished outcomes, but the process behind them.

## Tech Stack

- Single-file HTML, CSS, and JavaScript (no build step required)
- Deployed as a static site on [Render](https://render.com)

## Project Structure

```
Aboutme/
└── index.html   # Portfolio page (self-contained)
```

## Running Locally

No dependencies or build tools required. Clone the repo and open the file directly in a browser:

```bash
git clone https://github.com/Yasaswind24/Aboutme.git
cd Aboutme
open index.html   # or double-click the file
```

## Deployment

This site is deployed on Render as a **Static Site**:

1. Connect the GitHub repository to Render
2. Set the **Publish directory** to `.` (repo root)
3. Push to `main` — Render auto-deploys on every commit

## Updating Content

Since the portfolio is a single HTML file, edits are made directly in `index.html`. Commit and push to `main` to trigger a redeploy.

## License

This project is personal portfolio content and not licensed for reuse.
