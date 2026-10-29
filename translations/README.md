# Translating Poni

Poni is in English, and the next version adds a language setting with Bahasa Indonesia. You can help it speak your
language too, or fix a word that reads wrong. This folder only holds Poni's texts; the app's source code isn't here.

## The files

| File | What it is |
|---|---|
| `en.json` | Every text Poni shows, in English. Use it as a reference. |
| `id.json` | Bahasa Indonesia (complete). |
| `ar.json` | Arabic (open: every text is there, the translations are still empty). |

Each line is `"English text": "translation"`. Only the right-hand side is yours. A translation left empty (`""`) shows
in English for now, so you can translate a bit at a time and still try it out.

## How to help

1. **A new language?** Open an issue and say which one. I'll add an empty file for it, with every text in place.
2. **Translate:** fill in the right-hand side of your language's file. Don't change the English on the left.
3. **Send it:** a pull request, or attach the file to your issue. Halfway is fine.
4. **Try it:** I'll send you a test build so you can see your words in Poni before it's released (Settings → General
   → Language).

## A few rules

- Keep words in braces exactly as they are: `{n}`, `{name}`, `{time}`… Poni fills them in. You can move them around in
  the sentence: `"{n} minutes"` → `"{n} menit"`.
- Keep HTML tags like `<b>…</b>`, `<br>` and `<kbd>…</kbd>` around the same words.
- Text after a `|` in a key is a note about what the word means: `"Clear|weather"` is clear sky, not a Clear button.
  Translate the word only.
- Names stay as they are: Poni, Windows, Spotify, GitHub, Wi-Fi, Bluetooth, and keys like Ctrl, Alt, Win.
- Buttons, tabs and menu items have little room: the shorter natural word wins.
- Don't use straight quotes `"` or `'` inside a translation (some texts go into HTML attributes). Use your language's
  quote marks or “ ” ‘ ’.
- Write it the way people talk to an app they like: plain and friendly, not formal.

## Right-to-left languages

For Arabic, Hebrew, Persian and Urdu, Poni mirrors its whole layout by itself (right to left). To see how your
translation fits before it's done, Settings → General → Layout direction → Right to left mirrors Poni in any language.
Arrows such as "Settings → About" in a text can point the other way in your language: use ← where that reads better.

## When Poni gets new texts

New texts are added to every file with an empty translation, and nothing you've translated is touched. The files here
are updated with each release.
