# FlipCard Trainer MVP Implementation Plan

**Goal:** Build a single-page web app for KL to study paired information through a card game interaction: covered card → question → answer.

**Architecture:** One standalone `index.html` containing HTML, CSS, and vanilla JavaScript. Data is stored in browser `localStorage`; import/export uses JSON. Default deck is 地支十二時辰.

**Tech Stack:** HTML, CSS, vanilla JavaScript, browser localStorage. No backend, no build step.

---

## MVP Scope

- Default deck: 地支十二時辰.
- Responsive card grid.
- Card states: covered → question → answer → covered.
- Shuffle cards.
- Reset all cards.
- Mark answer as 識 / 唔識 / 再溫.
- Track seen/correct/wrong/review counts per card.
- Create/edit/delete decks.
- Add/edit/delete cards.
- JSON import/export.
- Save everything locally in browser.

## Validation

- Static file exists and has app shell.
- JavaScript has no syntax errors when extracted and checked with Node.
- Automated DOM-free logic smoke test verifies default deck count and card state cycle.

## Files

- `/opt/data/projects/flipcard-trainer/index.html`
- `/opt/data/projects/flipcard-trainer/docs/flipcard-trainer-mvp-plan.md`
