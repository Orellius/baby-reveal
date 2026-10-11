# Baby Reveal

Read [the category rules](../README.md) first.

## Commands

- Preview: `python3 -m http.server 8731` in the repo root, then open http://localhost:8731 (verified 2026-10-11).
- Cover variant: the default is black foil. Add `?cover=split` for half pink, half blue.
- Publish: push to `main`. GitHub Pages serves the repo root.
- The answer is XOR-encoded in `index.html` (`const P`). Never write it in plain text in the repo, the README or a commit message.
