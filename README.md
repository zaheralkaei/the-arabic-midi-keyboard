# The Arabic MIDI Keyboard

A browser-based MIDI keyboard for Arabic music, combined with a drum machine. Play quarter-tone notes (essential for maqam music) with your computer keyboard, touch screen, or mouse, and lay down beats with the built-in drum machine. Designed to run in any modern browser — no install, no build.

Live demo: https://thearabicmidikeyboard.netlify.app/

## Features

- **Quarter-tone support** — the black keys play the half-flat notes used throughout Arabic maqamat (E half-flat, B half-flat, etc.)
- **2 or 3 octaves** — toggle how many octaves of the keyboard you want to play
- **Computer keyboard mapping** — A row of your QWERTY keyboard maps to one octave
- **Touch / mouse click** — every key is also clickable
- **Hold button** — sustain notes while you play
- **Drum machine** — pattern sequencer with standard, cajon, and electro kits
- **Preset patterns** — quick-start rhythms for the drum machine

## How to use

Open `index.html` in a modern browser (Chrome, Firefox, Safari, Edge). No server, no install.

- **Click any key** to play it
- **Hold a key on your QWERTY keyboard** — the bottom row maps to the lower octave, the second row to the upper octave
- **Toggle the hold button** to keep notes sustained
- **Use the drum machine panel** to build beats

## Run from disk

Single self-contained HTML file, no dependencies beyond the embedded Tone.js loaded from a CDN. Just open it.

If your browser is fussy about local file access, you can serve the folder:

```
python -m http.server 5555
# then open http://localhost:5555
```

## Libraries used

- **Web Audio API** — for generating and controlling audio
- **Tone.js** — loaded from CDN; a framework built on Web Audio API to simplify interactive music

## License

MIT. See [LICENSE](LICENSE) (if present in this repo).

## About

This is a v2 that merged the original Arabic MIDI Keyboard and a separate Drum Machine into a single application. See the in-page "About" panel for the original changelog.

---

Built by [Zaher Alkaei](https://github.com/zaheralkaei).
