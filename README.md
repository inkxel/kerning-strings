# Kerning Strings

A set of proofing strings for spacing and kerning typefaces — the exact text I paste into [Glyphs](https://glyphsapp.com/) to work through every letter pair systematically. Years of refining these into a kit that catches the awkward combinations real text throws at you.

Free to use, no attribution required. See [License](#license).

## Why kerning strings

Kerning is the art of adjusting the space between specific letter pairs so text reads evenly. The trap is that some pairs almost never show up in casual typing — `rwf`, `Tz`, `jh`, `quumbabda` — but the moment they appear in real text, bad spacing is obvious. A good proofing string puts every problem pair in front of you on purpose, in context, so nothing slips through.

These strings are built to do that: real words and names that stress the hard combinations, plus exhaustive pair matrices for when you want to grind through the whole alphabet methodically.

## How to use them in Glyphs

1. Open your font in **Glyphs** and open a new **Edit View** tab (`⌘T`).
2. Open a file from [`strings/`](strings/), copy its contents, and paste into the tab.
3. Set the text large enough to judge spacing comfortably (~80–150 pt).
4. Walk the text. To adjust kerning, place the cursor between two glyphs and use `⌥←` / `⌥→` to add or remove kerning; hold `⌘` for larger steps. To adjust sidebearings (overall spacing), select a glyph and edit its metrics.
5. Re-paste and re-read after a pass — fresh eyes catch what tired ones miss.

Not a Glyphs user? The files are plain UTF-8 text. Paste them into any type tool — FontForge, RoboFont, Illustrator, InDesign, or a browser — set your typeface, and proof the same way.

## The files

| File | What it covers |
|------|----------------|
| [`proof-words.txt`](strings/proof-words.txt) | Real words and proper nouns chosen to exercise tricky pairs across lowercase and capitals. The everyday workhorse — read it like a page of text. |
| [`proof-words-accented.txt`](strings/proof-words-accented.txt) | The same word list with diacritics applied, to check spacing around accented characters. |
| [`pairs-caps.txt`](strings/pairs-caps.txt) | Every capital flanked by every other capital (`ABA…ZBZ`). Exhaustive cap-to-cap pair matrix. |
| [`pairs-lowercase-accents.txt`](strings/pairs-lowercase-accents.txt) | Lowercase doubles plus each diacritic surrounded by every letter — stress-tests accent spacing in lowercase. |
| [`pairs-caps-accents.txt`](strings/pairs-caps-accents.txt) | The capital version of the accent pair matrix. |
| [`kitchen-sink.txt`](strings/kitchen-sink.txt) | Full character set in one paste — letters, figures, punctuation, symbols, currency, math. A fast sanity check that nothing is wildly off. |

Start with `proof-words.txt` for the natural-reading pass, then drop into the `pairs-*` matrices when you want to be exhaustive.

## License

[CC0 1.0 Universal](LICENSE) — public domain dedication. Use them, fork them, ship them in your own tools, no credit needed. They're just text, and text should be free.

## Author

Made by David Tucker — type design and creative technology.
[davidtucker.me](https://davidtucker.me) · [@inkxel](https://instagram.com/inkxel)

If these saved you time, a link back is always appreciated but never required.
