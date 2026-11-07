# The Latte Factor

An interactive "receipt" that itemizes a daily habit — coffee, takeout, a subscription, whatever — and shows what that money would be worth if invested instead of spent.

Type in a habit and its cost, then drag three sliders (frequency, years, expected market return) and watch a dot-matrix chart race the flat "spent" line against the compounding "invested" curve.

## Try it

Just open `index.html` in a browser. No build step, no dependencies to install — it's a single self-contained file (HTML, CSS, and vanilla JS all in one place), pulling in Google Fonts for type.

## How it's built

- **Design**: a receipt-paper aesthetic — torn perforated edges, dot-matrix ledger lines, a brass/red ink color scheme, `IBM Plex Mono` for data and `Big Shoulders Display` for the stamped headline.
- **Math**: a standard future-value-of-an-annuity calculation (monthly contributions, monthly compounding) run against a straight-line sum of what was actually spent.
- **No frameworks**: plain HTML/CSS + a `<canvas>` for the chart, animated with `requestAnimationFrame`.

Built with [Claude Code](https://claude.com/claude-code) as a "vibe coding" exercise — directed and reviewed by a human, written by Claude.

## License

MIT — see [LICENSE](LICENSE). Fork it, remix it, make your own version of the habit you want to visualize.
