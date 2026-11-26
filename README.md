# AI Balance Wheel

An interactive wheel of balance for everyday AI use: nine areas of life, and four ways to use AI in each. The page content is in Russian.

**Live page:** https://julijakvetna.github.io/ai-balance-wheel/

## How it works

1. Pick a sector of the wheel: Health, Work, Money, Family, Friends, Growth, Rest, Home or Community.
2. Climb the four steps:
   - **Chat** – you ask, it answers.
   - **Project** – it remembers your files.
   - **Scheduled task** – it starts by itself.
   - **Agent** – it acts, you approve.
3. Each step opens a card with the tool, what to prepare, a prompt to copy, and the point where a human says yes.

Each step lists real published stories (with source link, date and a confidence note) plus a few demo ideas, each tagged with the tools used (ChatGPT, Claude, NotebookLM, Gemini and others). The stories were collected by research agents and the links have not all been checked by hand.

## Use it

The page is a single self-contained `index.html` with no build step. Open it in a browser, or host it anywhere that serves static files. Left and right arrow keys move between steps.

To change a scenario, edit the `DATA` array in `index.html`. Each case is one `C(...)` call: title, story, wow line, tool tags, what to prepare, prompt, where the human says yes, then source name, date, link and confidence. A case with no source is shown as a demo idea.

## Background

Built for a talk on AI in daily life at Limmud FSU Portugal 2026, by Judith Kvetna Snagovska ([binah.ai](https://binah.ai)).
