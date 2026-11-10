# Money Match
A tiny, free finance memory game for a student mini-company.

## Play
https://joel-reimann.github.io/test-memory-game/

Match each finance term with its definition. Includes 6- and 8-pair rounds, a timer, move counter, short learning notes, and personal bests.

## Enable GitHub Pages (one time)
Repository Settings → Pages → Source: **Deploy from a branch** → Branch: **main** → **/(root)** → Save.
GitHub will build the site; allow a few minutes for the first publication.

## Link from Jimdo
Add a Button element (Creator), or enable a Primary/Secondary Button in a block (Website Builder).
Label it **Play Money Match**, choose an external URL, and paste:
https://joel-reimann.github.io/test-memory-game/

A normal button link works without running JavaScript inside Jimdo.

If your Jimdo editor supports a Widget/HTML element with iframes, you can optionally try:
```html
<iframe src="https://joel-reimann.github.io/test-memory-game/"
  title="Money Match finance memory game"
  width="100%" height="1100"
  style="border:0;border-radius:16px" loading="lazy"></iframe>
```
Whether embedding is available depends on the Jimdo editor and plan. The external link is the default.

## Demo sign-in
Nickname only; **this is not real authentication**. No passwords, accounts, backend, or shared leaderboard.
The nickname and personal bests are stored locally in the visitor's browser, with an in-memory fallback if storage is unavailable.
Do not enter sensitive information. Switching players changes the active nickname but does not delete saved personal bests.

## Customize
Edit `CONCEPTS` in `index.html` to change the terms, definitions, and lesson text. Keep concept IDs unique and provide at least 8 concepts.
Change the visible “money match” text and CSS colors to match the mini-company.
The game is plain HTML/CSS/JavaScript: no dependencies, install step, or build command.
Open `index.html` directly to try it locally. Fonts load from Google Fonts when available; system fonts are the fallback.

## Teaching ideas
Ask students to add a concept, explain the difference between revenue and profit, or redesign the cards to match their finance book.
