# music/

Drop `.mp3` or `.m4a` files in this folder and every phone that scans into a game
plays them as a shuffled background loop (at low volume, under the game sound FX).

- **On GitHub Pages** (the normal setup): any filename works — the game lists this
  folder through the GitHub API.
- **On any other host**: name the files `music01.mp3`, `music02.m4a`, `music03.mp3`, …
  with no gaps in the numbering.

Playback starts on the player's first tap (browsers block audio before a user gesture).
