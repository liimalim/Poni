# Translating Poni

Poni speaks English, Bahasa Indonesia and the languages below (Settings → General → Language). You can help it speak
your language too, or fix a word that reads wrong. This folder only holds Poni's texts; the app's source code isn't
here.

## The files

| File | What it is |
|---|---|
| `en.json` | Every text Poni shows, in English. Use it as a reference. |
| `id.json` | Bahasa Indonesia (complete). |
| `fr.json` | French (complete, by MaximeDawn). |
| `pl.json` | Polish (complete, by kasper-pawlowski). |
| `tr.json` | Turkish (complete, by ferdibisus). |
| `ar.json` | Arabic (complete, by M07amedHassan99). |
| `uk.json` | Ukrainian (complete, by MrBooomber). |
| `ru.json` | Russian (complete, by Jemmrock). |
| `zh.json` | Simplified Chinese (complete, by HumorSeth). |
| `ja.json` | Japanese (complete, by rogervokma-stack). |
| `es.json` | Spanish (complete, by Snoku). |
| `vi.json` | Vietnamese (complete; corrections welcome). |
| `languages.json` | The list of languages Poni offers. |

Each line is `"English text": "translation"`. Only the right-hand side is yours. A translation left empty (`""`) shows
in English for now, so you can translate a bit at a time and still try it out.

## How to help

1. **A new language?** Open an issue and say which one. I'll add an empty file for it, with every text in place.
2. **Translate:** fill in the right-hand side of your language's file. Don't change the English on the left.
3. **Send it:** a pull request, or attach the file to your issue. Halfway is fine.
4. **Try it:** from Poni 1.6.0 on, there's no waiting for a release. Poni checks this folder once a day: a fix merged
   here is used from its next start, and a new language shows up in Settings → General → Language once it's added to
   `languages.json`. Texts added to Poni since are filled in for you, and corrections are always welcome.

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
are updated with each release. Texts an older Poni still uses stay in the files, so older versions keep theirs.
