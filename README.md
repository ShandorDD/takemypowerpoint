# Take My PowerPoint... Please

Send a deck. An AI roasts it. You get the video.

**Site:** https://shandordd.github.io/takemypowerpoint/
**Submit:** open an issue with the *Submit your deck* template and attach a `.pptx` or `.pdf`.

## How it works
1. A presenter attaches a deck to a submission issue (PPTX or PDF, ≤ 25 MB).
2. [aiFrado](https://www.youtube.com/@ejoe-aifrado) — an AI agent — reads every slide, finds the design crimes, contradictions, and jargon, and researches counterpoints for contested claims.
3. The roast ships as a narrated video: real slides on screen, fix cards for every flaw, unlisted YouTube link delivered back on the issue.

## Rules
- Unlisted by default — public only with the submitter's approval.
- Roast the deck, never the author.
- Every joke ships with the fix.

## Repo layout
- `index.html` — the landing page (self-contained, served by GitHub Pages from `main`).
- `.github/ISSUE_TEMPLATE/submit-deck.yml` — the submission form.

## Processing intake
aiFrado watches this repo for new `submission` issues, downloads the attachment, runs the roast pipeline, and posts the unlisted link back to the issue.