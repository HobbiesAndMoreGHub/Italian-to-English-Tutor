# Italian Learning Center

A comprehensive Italian language learning application built entirely with HTML, CSS, and JavaScript. No server required — runs locally in your browser.

## Features

- **Quick Import** — Bulk import words (Italian-to-English or English-to-Italian) with AI translation via Claude API, plus a built-in 6,000+ word dictionary
- **Word Bank** — Save, search, sort, and manage your vocabulary with easy/hard difficulty markers
- **Flashcards** — Study with flip cards, weighted shuffle (hard words appear more, easy less), conjugation display, keyboard shortcuts
- **Memory Game** — Card matching game pairing Italian and English words, with configurable difficulty
- **Audio Scripts** — Generate and play audio study scripts with adjustable speed, repetition, and voice selection
- **Dashboard** — Track your learning progress with stats on words learned today, this week, this month

## Getting Started

1. Open `index.html` in your browser (Chrome recommended)
2. Go to the Quick Import tab and click "Load Built-in Dictionary" to load 6,000+ words
3. Optionally, click "API Settings" in Quick Import and add your [Anthropic API key](https://console.anthropic.com) for AI-powered translations
4. Start studying with Flashcards, Memory Game, or Audio Scripts

## Keyboard Shortcuts (Flashcards)

| Key | Action |
|-----|--------|
| Space / Enter | Flip card / Next card |
| Arrow Left/Right | Previous / Next |
| 0 | Toggle Easy |
| Ctrl / H | Toggle Hard |

## API Key (Optional)

The Claude API key enables:
- Bulk word translation in Quick Import
- Grammar and conjugation data

Without an API key, the app still works with the built-in dictionary and manual word entry.

## Data

All data is stored in your browser's localStorage. Use **Backup All Data** / **Restore Data** in the Word Bank tab to export/import your complete learning data.

## Credits

Created by **John R.** & **Claude** (Anthropic)

## License

MIT License — free to use, modify, and distribute.
