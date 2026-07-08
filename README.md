# goatyler.com 🐐

**The hub for everything Tyler builds.**

[goatyler.com](https://goatyler.com) is my personal corner of the internet — a single landing page that links out to every game, app and experiment I've shipped (and teases the ones I haven't yet). Think of it as a link-in-bio page that went to art school and came back with a pixel goat.

## What's on it

The page is one screen: a bobbing pixel-art goat, the **goatyler** wordmark (goat + tyler share a *t* — efficient), and **The Paddock**, a grid of glowing cards, one per project. The newest thing gets pinned full-width at the top:

- 📟 **Glance** — turns a tiny 3.5″ USB screen into a live, build-it-yourself PC dashboard

- ⛳️ **PuttQuest** — 8-bit minigolf for iOS *(coming soon)*
- 🌀 **PortalJam** — slide-blocks-through-portals puzzler for iOS *(coming soon)*
- 🧩 **Badoku** — sudoku with attitude, for iOS & Android
- 🏒 **Neon Hockey** — air hockey meets tennis, playable in the browser
- 📦 **Panic Packet** — a 60-second retro delivery sprint, on mobile or PC
- 🐑 **Pixel Sheep Alchemist** — clicker alchemy with humble sheep
- 🧱 **Block Out** — a colour-sort puzzle that starts chill and turns evil
- 🧠 **Pixel Memory Test** — how long a number can you actually hold in your head?

Cards that link to multiple platforms (like Badoku) open a little chooser menu instead of a single link.

## The Arcade

There's also a side door: a tab on the edge of the page leads to **[the arcade](arcade.html)** — three quick games built for this site and playable nowhere else:

- 🐐 **Goat Dash** — an endless fence-jumper. Space or tap to jump.
- 🔨 **Whack-a-Goat** — 30 seconds of bonking goats (+1) while sparing the innocent sheep (−2)
- ⚡ **Golden Reflex** — click the instant the panel turns gold; your reaction time gets judged by a goat

Best scores are saved in your browser. No coins needed.

## The fun bits

- **Command palette** — press `/` or `⌘K` and fuzzy-search your way to any project
- **Keyboard shortcuts** — `1`–`9` jump straight to a card
- **The goat** — click it. It bleats, with a proper 8-bit *meh*. Click it five times and you'll get a weather event 🐐🌧️
- Cards tilt toward your cursor and glow in their own colour
- A live clock from goat HQ in Sydney ticks away in the footer
- Even the [404 page](404.html) is a goat that wandered off

## Under the hood

The whole site is **plain HTML files** — no framework, no build step, no dependencies beyond a Google Font. The goat mascot is drawn at runtime from an ASCII pixel map, the bleat is synthesised with the Web Audio API, the arcade games are hand-rolled canvas and DOM, and everything respects `prefers-reduced-motion`.

**No cookies. No trackers. No ads. 100% goat.**
