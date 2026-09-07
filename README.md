# Life in the UK Test — Practice

A free, self-contained web app for practicing the "Life in the UK" citizenship/settlement test. This is the version I used and I passed the test today! It tracks your progress, collects your mistakes, and lets you come back and revise them.

**Live site:** https://sageeyuu.github.io/LifeInTheUkTest_Practice/

## Features

- Full mock test runner with a timer and question flagging
- Topic-by-topic readiness breakdown
- Flashcard deck for quick revision
- Automatic tracking of mistakes so you can focus revision on your weak spots
- Works entirely in the browser — no sign-up, no server, no data leaves your device

## Running locally

Just open `index.html` in a browser, or serve the folder with any static file server, e.g.:

```
python3 -m http.server
```

## Enabling GitHub Pages (for maintainers)

This repo includes a GitHub Actions workflow (`.github/workflows/pages.yml`) that deploys `index.html` to GitHub Pages on every push to `main`. To turn it on:

1. Go to **Settings → Pages** in this repository.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. Push to `main` (or re-run the workflow) — the site will publish to `https://sageeyuu.github.io/LifeInTheUkTest_Practice/`.
