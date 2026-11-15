# Dapple

One home for four games, made to be played on two phones.

- `index.html` – the Dapple home screen, where you pick a game.
- `hue/` – **Hugh**, a colour matching game (duel, card swap, solo streak). Source of truth used to be the HueMatchMe repo.
- `paddle/` – **Paddle Draft**, an auction draft game for two to six players. See `paddle/README-paddle-draft.md`.
- `glass/` – **Glass Half Full**, a splitting duel. Each round you both get the same object (a baguette, a fish, a pencil, a glass of lemonade…) with a random but realistic size and weight, and cut it into two halves of equal weight or length, or pour the glass exactly half full. Closest to a perfect half deals the gap in damage, Hugh-style.
- `angle/` – **What's Your Angle?**, an angle duel. Some rounds name an angle and you swing an arm round to make it; others show an angle and you guess its size. The Perfect Round mode has you draw a circle freehand, scored on roundness. Closest deals the gap in damage, Hugh-style, and there's a Solo Streak too.

Each game is a self-contained page that pairs phones with a four-letter room code (PeerJS). Saved games and room codes are stored per game, so they never mix. Add Dapple to your home screen and all the games open inside the one app.

Hosted with GitHub Pages from the `main` branch root.
