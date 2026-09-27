# Tidy Rush — dev notes

How Tidy Rush was built, for the curious. Players start at the [itch.io page](https://oopsallfalling.itch.io/tidy-rush).

- Built September 2026 — the first of three planned cleaning games (each its own game, not modes).
- One self-contained HTML file. No frameworks, no build step, no backend.
- 128-object pool (32 per category), 16 drawn per round, every item labeled after playtesting said the icons were unclear.
- Art direction picked from three cover options; the whole game was restyled to match the cut-paper collage winner.
- Score card carries a scannable QR code (generated offline, inlined library) so every share is a funnel back to the game.
- Deployed via GitHub Actions + itch.io butler: every push to `tidy-rush/**` updates the live build.

Unadvertised mirror (please play on itch.io so the stats count): https://yuanb10.github.io/OopsAllFalling/tidy-rush/
