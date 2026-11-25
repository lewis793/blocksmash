# Block Smash

A block puzzle with an honest dealer. No ads, no revives, works offline.

- Pieces are uniformly random (`crypto.getRandomValues`). The dealer never looks at your score.
  Its only rule: it re-deals if a piece couldn't fit anywhere on the board.
- Clear 10 lines to charge **SMASH**, then blow up any 2×2 area.
- Modes: Classic, Daily (same deal for everyone, one game a day), Timed (2 minutes), Zen (no game over).

Font: [Lilita One](https://fonts.google.com/specimen/Lilita+One) by Juan Montoreano, SIL Open Font License 1.1, bundled in `fonts/`.

## Install on your phone
Open the GitHub Pages link once, then:
- **iPhone:** Safari → Share → *Add to Home Screen*
- **Android:** Chrome → menu → *Install app*

After that it runs fully offline.

## Run locally
`python -m http.server 8765` then open http://localhost:8765
