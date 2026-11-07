# The Latte Factor

NOTHING SERIOUS. An interactive "receipt" that for a daily habit. From coffee, takeout, a subscription, etc.. and shows what that money would be worth if invested instead of spent.

Type in a habit and its cost, then drag three sliders (frequency, years, expected market return) and watch a dot-matrix chart race the flat "spent" line against the compounding "invested" curve.

## Try it

Just open `index.html` in a browser. No build step, no dependencies to install, it's a single self-contained file (HTML, CSS, and vanilla JS all in one place), pulling in Google Fonts for type.

## How it's built

- **Design**: a receipt-paper aesthetic: torn perforated edges, dot-matrix ledger lines, a brass/red ink color scheme, `IBM Plex Mono` for data and `Big Shoulders Display` for the stamped headline.
- **Math**: a standard future-value-of-an-annuity calculation (monthly contributions, monthly compounding) run against a straight-line sum of what was actually spent.
- **No frameworks**: plain HTML/CSS + a `<canvas>` for the chart, animated with `requestAnimationFrame`.

Built with [Claude Code](https://claude.com/claude-code) as a "vibe coding" exercise for fun!!! Directed, altered and reviewed by a human, written by Claude Code.

## License

MIT — see [LICENSE](LICENSE). Remix it and make it your own, do a version of whatever habit you want to visualize. 
