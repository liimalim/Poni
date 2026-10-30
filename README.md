# Poni

An interactive notch for Windows 10 and 11 (formerly "Notch for Windows"). It lives at the top of your screen: hover over it to open it, drag files onto it, or press `Alt+N`.

**[Download the latest version](https://github.com/liimalim/Poni/releases/latest)**: pick `Poni_x.y.z_x64-setup.exe` (recommended, updates itself) or the portable `.exe`. Website: **[poni.web.id](https://poni.web.id/)**. How to use every feature: **[the Poni guide](https://poni.web.id/en/guide/)**.

## Features

- **Music**: album art with color glow, live visualizer, and controls for any player in the Windows media controls (Spotify, browsers and more) and VLC, plus **lyrics** that follow the song (from LRCLIB, off until you turn them on), right inside the closed notch if you like, with Korean, Japanese and Chinese lyrics in Latin letters or translated, and a song progress bar
- **Dashboard**: weather, quick toggles (Wi-Fi, Bluetooth, keep awake, dark mode, mute mic, lock), app launcher, day progress, prayer times
- **Control**: like Windows Quick Settings, with Wi-Fi and Bluetooth lists, toggles, brightness and volume sliders, and picking the sound output and microphone
- **Calendar**: Google Calendar, Outlook or any iCal (.ics) link, with meeting reminders in the notch, a Calendar tab with a month view, and event details with a Join button
- **Todo** with due times you can type in everyday words (Indonesian or English), repeating tasks, snooze, and a countdown in the closed notch where you can tick tasks off; late tasks can tick themselves off. **Notes, Pomodoro** with a stopwatch, **Weather, Health** (water with reminders, breaks, breathing, 20-20-20 eye breaks)
- **Prayer times**: a Prayer Times tab and reminders for the five daily prayers with a countdown in the closed notch (the Kemenag RI schedule in Indonesia, your local authority elsewhere), and an adhan from your own recording
- **Dock**: a bar of your apps at the bottom with magnifying icons in one rounded shape, in five styles (Black, White, Clear Glass, Frosted Glass, Midnight), on one display or all of them. It can stand in for the Windows taskbar with a Start and a Task View button, your other apps' tray icons (left and right click), a keyboard language menu, the time and status, the next prayer and a Show desktop button, and lists an app's windows when you rest the mouse on it (off until you turn it on)
- **FPS counter** for games, with CPU and GPU, in the closed notch (off until you turn it on; Windows asks for permission once)
- **Wi-Fi & Bluetooth**: radio switches, join Wi-Fi networks right in Poni, connect/disconnect headphones and speakers, device battery levels
- **Screen Time, Day Progress, System stats** with CPU and GPU load and temperatures (when Windows shares them, no admin or driver needed), and a System summary that pops up in the closed notch now and then
- **Shelf and Drop Actions**: zip, extract, convert images, copy/move, OneDrive, Share, Recycle Bin
- **Snap Zones**: drag a window onto the notch to tile it
- **Your look**: Poni in black, any color, glass, or frosted glass, attached to the top edge or floating a little below it
- **The closed notch**: pick what its left and right show (weather, battery, date, next prayer, event, task, temperature, CPU, memory, disk or Wi-Fi), a clock in the middle that stays while music plays, **auto-hide** (always, or while the apps you pick are in front) that can come down while you're idle, and a hide button (or a double right-click) that tucks Poni away to a thin handle
- **Touchscreen support**: taps on Poni reach Poni, taps beside it go to the window behind
- **Windows notifications in Poni**: messages, mail and browser notifications stack under the closed notch, each for as long as you choose, and a click opens the app; a history keeps them for a few days, they follow Do not disturb, and Poni can turn off Windows' own pop-up so they don't show twice
- **Cat Buddy**: a 3D cat under Poni that watches your mouse, bobs along to music and dozes off when you leave; click it to chat. On from the start, with five fur colors, or put your own picture (even a GIF) in its place
- **Cute cursors**: cat-themed mouse pointers in every app (a paw arrow, a paw for links, a ball of yarn while loading) in seven colors, or your own cursor pack; Windows' own come back when you turn them off
- **HUD** for volume, brightness, Caps Lock / Num Lock, airplane mode, the microphone and the touchpad; Poni can hide Windows' own brightness pop-up and your laptop maker's boxes while it shows the same thing
- **AI Chat** and **Translate** with Google Gemini (free API key from Google AI Studio), Claude, any OpenAI-compatible API, or local Ollama. AI Chat knows your day and how your PC is doing, can add todos, reminders, notes and calendar events, start Pomodoro or open your apps, with Undo, and can send you a brief on the days and times you pick
- **Radio**: internet radio stations from Radio Browser, with favourites, right in Poni (off until you turn it on)
- **Bookmarks**: save links in your own categories; copy a link and save it in one click (off until you turn it on)
- **Languages**: English and Bahasa Indonesia (following Windows by default), right-to-left layouts, and [translation files](translations/) anyone can help with
- **Back up and restore** Poni's settings and data to move to another PC
- **GitHub** pull requests waiting for your review

## Updates

The installed (Setup) version checks this page for new versions and updates itself (Settings → About). Every update is signed, so Poni only installs files signed by the author. The portable version shows a notice instead.

Coming from Notch for Windows? Nothing to do: Notch updates itself to Poni, removes the old install and keeps your settings, todos and notes.

## Support

Poni is free. If it helps you, you can treat the developer to a coffee:

- **[Support on Gumroad](https://bosdigital.gumroad.com/l/notch-for-windows)** (international: card or PayPal, pay what you want)
- **QRIS** (Indonesia: GoPay, OVO, DANA, ShopeePay, mobile banking)

  <img src="assets/qris.jpg" alt="QRIS Bos Digital" width="260">

In Poni, click the cup button next to the settings gear (or open Settings → About). Made by **Alim AJ** · Bos Digital.

## Requirements

Windows 10/11 64-bit with Microsoft Edge WebView2 (already included in Windows 11 and up-to-date Windows 10).

Listing Wi-Fi networks needs location access for desktop apps on Windows 11 (Settings → Privacy & security → Location); Poni shows a button for it.

Windows SmartScreen may warn on first run because the app isn't code-signed with a paid certificate: click **More info → Run anyway**.

## Privacy

Everything stays on your PC (`%APPDATA%\Poni`). Network is only used for these: weather (Open-Meteo, on from the start), prayer times (api.myquran.com in Indonesia, Aladhan elsewhere), your calendar links, GitHub, AI chat and translation (the provider you pick), lyrics (LRCLIB, if you turn them on) and album art Windows doesn't give (Deezer), radio stations (Radio Browser, if you turn the Radio tab on), the title and icon of a link you bookmark, and update checks. Once a day the update check adds one to that day's usage count on poni.web.id, counted by country as Cloudflare reports it, and that's all (no ID for your PC, no version or language; only today's numbers are kept, no IP addresses) so we know how many people use Poni and where; turn it off in Settings → About and updates are checked on GitHub directly. AI chats stay on this PC, the notification history is kept encrypted on this PC, Windows notifications shown in Poni, the Dock's tray icons and the FPS counter's frame counts are read on this PC and never sent anywhere, and the optional VLC web interface is only reached on this PC.

## What's new

What changed in every version: **[release notes](https://poni.web.id/en/release-notes/)** ([Bahasa Indonesia](https://poni.web.id/catatan-rilis/)).

---

**Bahasa Indonesia:** Poni adalah notch interaktif di bagian atas layar Windows (dulu bernama Notch for Windows). Unduh **Setup** dari [Releases](https://github.com/liimalim/Poni/releases/latest) supaya Poni bisa update otomatis. Cara pakai semua fiturnya ada di [Panduan Poni](https://poni.web.id/panduan/). Kalau Poni bermanfaat, kamu bisa traktir developernya lewat QRIS di atas.
