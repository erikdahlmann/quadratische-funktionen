# Quadratische Funktionen · Mathematik Klasse 9

Live: https://erikdahlmann.github.io/quadratische-funktionen/

Interaktive Lernseite zum schulinternen Lehrplan **9.2 Quadratische Funktionen**
(17 UE) am Paul-Klee-Gymnasium Overath.

Zehn Kapitel: Parabeln im Alltag, Normalparabel, Streckfaktor, Scheitelpunktform
(Scheitel ziehbar), Ablesen aus dem Graphen, quadratische Ergänzung mit animierter
Herleitung, Nullstellen und faktorisierte Form, eine echte Messreihe mit
Fehlerbalken, ein Extremwertproblem und ein Selbsttest. 40 Aufgaben mit
Selbstkontrolle, Lösungswegen und gespeichertem Fortschritt.

## Bauen

```
python3 build.py
```

Baut aus `src/` die eine Datei `index.html` (ca. 250 kB). CSS, Daten, Logik und
Anime.js sind eingebettet; die Seite öffnet per Doppelklick und läuft ohne Netz.
Nur `bilder/` bleibt als Ordner daneben.

## Ordner

| Ordner | Inhalt |
|---|---|
| `src/` | Quellen: `stil.css`, `inhalt.html`, `daten.js`, `app.js` |
| `lib/` | `anime.umd.min.js` (Anime.js 4.5.0, MIT) |
| `bilder/` | sieben KI-Bilder als WebP |
| `original/` | die alte Seite, unverändert |
| `_planung/` | Bildprompts, Rohbilder, Codex-Protokolle (nicht veröffentlichen) |
| `PRUEFUNG.md` | Prüfbericht zur alten Seite: Rechenprobe, Programmfehler, Didaktik |

## Herkunft

Überarbeitung von `dm-quadratische-funktionen-nf-spf` (Gemini 3 Pro, Januar 2026).
Die Aufgabendaten beider alten Aufgaben wurden nachgerechnet und übernommen,
alles andere ist neu. Einzelheiten in `PRUEFUNG.md`.

Bilder mit ChatGPT (gpt-image) über die Codex-CLI erzeugt, Prompts in
`_planung/bildprompts.md`.
