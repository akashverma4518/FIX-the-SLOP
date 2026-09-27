# MegaCorp Ultra Portal 2000™

Welcome to the worst website in the world. Your job is to rescue it.

## The site
| Page | File |
|---|---|
| Home (3D + motion) | `index.html` |
| Admin dashboard | `admin.html` |
| Blog | `blog.html` |
| Contact / community forum | `contact.html` |
| Tools (calculator suite) | `tools.html` |

It's frontend only: no backend, no build step. Open `index.html` or serve the folder with any static server.

## Your mission
Find and fix the problems on **all five pages**. This is a repair job, not a rebuild: fix the site in place.
Every tool, the dashboard numbers, the blog, the forum and the contact form must work (correctly).

> **Read [`RULEBOOK.md`](RULEBOOK.md) before you start.** AI prompts must name a specific problem you found yourself.
> Prompts that ask to redesign, recreate, rebuild or "find all bugs" are banned. You must submit every AI chat, complete.

## You'll be judged on
1. **UI / UX**: visual design, hierarchy, consistency, navigation
2. **Accessibility**: keyboard, screen reader, contrast, motion, semantics
3. **Functionality**: every feature works and is *correct*
4. **Theme**: a coherent design system, working light/dark mode
5. **Performance**: load speed, Lighthouse scores, bundle size
6. **Tech stack**: sensible choices, clean code, justified dependencies
7. **Responsiveness**: phone, tablet, desktop

## Submission
- A public GitHub repo
- A live link (GitHub Pages, Netlify, Vercel, etc.)
- A `CHANGES.md` covering what you found and what you fixed, with each fix tagged to its chat
- A `chats/` folder with every AI chat, complete (share links, `.md` or `.json`); see `RULEBOOK.md`

Scoring: **Quiz 40% + Website fix 60%**. The full breakdown is in `RULEBOOK.md`.

Good luck. You'll need it. 🦆


## Competition update

This version focuses on practical UX and performance improvements: cleaner first paint, accessible navigation, working theme persistence, less intrusive popups, responsive layouts, reduced 3D rendering cost, reduced dependency duplication, keyboard-friendly controls, and a guarded media playback call.

### Run locally
Open `index.html` with a static server such as VS Code Live Server.

### Deploy
This is a static HTML/CSS/JavaScript site and can be deployed with GitHub Pages, Netlify, or Vercel.
