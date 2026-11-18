# Abpfiff!

Ein Puzzle im Stadion: Die Gästefans haben mal wieder beim FC Hollywood verloren. Schick die Busse in der richtigen Reihenfolge in die Busbuchten, damit alle Fans nach Hause kommen.

Ableger von Abflug! (gleiche Spiellogik, eigenes Thema, eigener Spielstand). Alles steckt in einer einzigen Datei, `index.html`, ohne Bibliotheken.

- Teams: Spitznamen statt Vereinsnamen, keine Wappen. Farben in `DEST` in `index.html`.
- Manu (Torwart, bremst) und Phonzie (Außenverteidiger, sprintet) sind freundliche Comic-Persiflagen.
- Gästefans als Comic-Tiere je Team (Biene, Ork, Adler, Geißbock, Dino, Krokodil, Fohlen, Fisch, Bär, Teufel), keine offiziellen Maskottchen.
- Ausbau auf Plätzen (`SLOTS`, `SHOP`): Arena innen links und rechts vom Kreisel, Weg von der U-Bahn neben dem Busparkplatz. Pro Platz mehrere Teile, eines steht sichtbar.
- Einfache Figuren: Umschalter im Startschirm und im Menü, oder Link mit `?einfach`.
- Tests: `node tests/levels.test.mjs`
- Seite für GitHub Pages bauen: `scripts/pages.sh` (schreibt `docs/`).
