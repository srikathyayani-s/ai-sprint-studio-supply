# AI Sprint Studio — Supply Side

Landing page for practitioners and builders interested in contributing to AI Sprint projects.

## What This Is

AI Sprint Studio connects skilled engineers, data scientists, and ML practitioners with companies that need focused AI solutions — built in short, outcome-driven 1–2 week sprints. This repository is the **supply-side** enrollment site where contributors discover open projects and submit applications.

The program is part of the **Skill Forward** AI upskilling initiative, organized by [Escape with Velocity](https://suresh-srinivas.github.io/skill-forward/) and Worksystems Oregon, funded by a Federal grant to expand access to in-demand AI skills.

## Project Types

Ten sprint project categories are currently open:

1. Internal Knowledge Assistants
2. Customer Support Summarization
3. Workflow Automation
4. Document Extraction & Processing
5. AI Search & Retrieval Systems
6. Sales Call & Meeting Summarization
7. Engineering Knowledge Search
8. AI Copilots for Business Workflows
9. Rapid AI Proof-of-Concept Prototypes
10. AI Readiness & Implementation Assessments

## Tech Stack

- Pure HTML/CSS/JS — no build step, no dependencies
- Formspree for application form submission (with optional video upload)
- Google Fonts: Newsreader, Manrope, JetBrains Mono
- Light/dark theme toggle with `localStorage` persistence

## Local Development

Open `index.html` directly in a browser — no server required.

## Form Setup

The application modal submits to Formspree. The endpoint is configured in `index.html`:

```js
const FORMSPREE_ENDPOINT = 'https://formspree.io/f/xdajrkvk';
```

To change the recipient emails, update the **Email Notifications** settings in the Formspree dashboard for that form ID.

## Deployment

Static site — deploy to any static host (GitHub Pages, Netlify, Vercel, etc.) by serving `index.html` from the root.
