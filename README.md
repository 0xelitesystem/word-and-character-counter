# Word and Character Counter

Paste text and get a live count of words, characters, sentences, paragraphs, and reading time. No server, no tracking, no third-party scripts.

**Live demo:** https://0xelitesystem.github.io/word-and-character-counter/

## Use

Open `index.html` in any modern browser, or visit the GitHub Pages link in the repo description.

Type or paste text into the box and the stats update on every keystroke:

- **Words** (runs of non-whitespace)
- **Characters** (including spaces)
- **Characters without spaces**
- **Sentences** (split on `.`, `!`, `?`, with runs like `...` or `?!` counted once)
- **Paragraphs** (blocks separated by blank lines)
- **Reading time** (estimated at 200 words per minute)

There are buttons to load a sample, copy your text back out, and clear the box.

## Why this exists

Word counters online are some of the most ad-saturated, tracker-heavy pages on the web, all to count text your browser already holds. This is the same idea, single file, no analytics, no signup, MIT licensed.

## Privacy

Everything runs in your browser. The text you paste never leaves your machine. Verify by viewing the page source or by opening DevTools and watching the network tab, no requests are made.

## Run locally

```bash
git clone https://github.com/0xelitesystem/word-and-character-counter
cd word-and-character-counter
# Open index.html in your browser, or:
python -m http.server 8000
```

## Contribute

Issues and PRs welcome:

- Counting edge cases (abbreviations, CJK text, emoji)
- Adjustable reading speed
- UI improvements (keep it minimal, no frameworks)
- Translations

Don't add: analytics, tracking, external scripts, npm dependencies. The whole point of this tool is no surveillance.

## Build

There is no build. It's a single HTML file.

## License

MIT.

## Related

- [url-parser-and-query-editor](https://github.com/0xelitesystem/url-parser-and-query-editor), break a URL into parts and edit query params
- [color-format-converter](https://github.com/0xelitesystem/color-format-converter), convert between HEX, RGB, HSL, and HSV
- [percentage-calculator](https://github.com/0xelitesystem/percentage-calculator), four common percentage questions in one place
