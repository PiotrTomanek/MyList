<!-- MYLIST README -->

<div align="center">

```
╔╦╗╦ ╦╦  ╦╔═╗╔╦╗
║║║╚╦╝║  ║╚═╗ ║ 
╩ ╩ ╩ ╩═╝╩╚═╝ ╩ 
```

**A brutally simple, obsessively minimal task manager.**  
*No accounts. No cloud. No nonsense. Just your list.*

[![Made with HTML](https://img.shields.io/badge/made%20with-HTML-000000?style=flat-square&logo=html5&logoColor=white)](.)
[![No Dependencies](https://img.shields.io/badge/dependencies-zero-000000?style=flat-square)](.)
[![License MIT](https://img.shields.io/badge/license-MIT-000000?style=flat-square)](.)

<br>

### → [**OPEN THE APP**](https://piotrtomanek.github.io/mylist/) ←

*Runs in your browser. Nothing to install.*

---

</div>

## WHAT IS THIS

MyList is a single-file HTML task manager that lives in your browser.  
No install. No login. No subscription. Open the file, use the app.

It looks like a poster. It works like a machine.

---

## FEATURES

```
✦  Carousel categories     — swipe between your worlds
✦  Swipe-to-delete         — satisfying, fast, irreversible (undo coming)
✦  Priority system         — URGENT / HIGH / MEDIUM / none
✦  Steps / subtasks        — break things down without drowning
✦  Groups within lists     — organize the organized
✦  Photo import via AI     — snap a handwritten list, watch it digitize
✦  Export to JSON / TXT    — your data stays yours
✦  Calendar export         — .ics for Apple & Google Calendar
✦  Zero dependencies       — one .html file, that's it
✦  Works offline           — always
```

---

## QUICK START

```bash
# Option A — just open it
open mylist.html

# Option B — serve it locally
npx serve .
# → http://localhost:3000/mylist.html

# Option C — host it anywhere
# Drop the file on Netlify, GitHub Pages, Vercel. Done.
```

No `npm install`. No `package.json`. No build step. No crying.

---

## THE PHOTO IMPORT THING

This is the party trick.

Take a photo of any handwritten list — grocery list on a napkin, whiteboard at the office, sticky notes on your monitor — and MyList will read it and import everything automatically.

**How it works:**
1. Tap **SCAN** in the top right
2. Enter your [Claude API key](https://console.anthropic.com/) *(stored locally, never sent anywhere else)*
3. Upload a photo
4. Watch it parse your chaos into organized tasks
5. Edit anything before importing

> The API call goes directly from your browser to Anthropic. This app never sees your key.

---

## HOW TO USE IT

### Navigation
| Action | How |
|--------|-----|
| Switch categories | Swipe left/right **or** arrow keys |
| Add a task | Tap **+** (bottom right) |
| Check off a task | Tap the checkbox |
| Delete a task | Swipe left on it |
| Edit task text | Tap it and type |
| Rename a category | Tap the big title and type |

### Categories
The **URGENT** category is special — it automatically pulls in every task across all your lists that's marked urgent. Think of it as your daily hit list.

Everything else is yours to name. Work. Home. Side project. Guilt. Whatever you need.

### Priority System
```
URGENT   →  Shows up in the URGENT view. Fix this today.
HIGH     →  Important. Don't forget it.
MEDIUM   →  Noted. Eventually.
(none)   →  It's on the list, relax.
```

### Steps / Subtasks
Long-press the `+ STEPS` button on any task to break it into numbered steps. Great for multi-part tasks you always forget half of.

---

## DATA & STORAGE

Everything lives in `localStorage` — your browser's built-in storage.

**Your data never leaves your device** unless you explicitly export it.

```
Export options:
  → JSON    (full backup, re-importable)
  → TXT     (human-readable)
  → .ICS    (calendar, works with Apple/Google)
  → Copy    (paste anywhere)

Import options:
  → From file   (.json backups)
  → Paste JSON  (from clipboard)
  → Photo scan  (AI-powered, requires API key)
```

---

## TECH STACK

```
HTML        ████████████████  100%
CSS         ████████████████  100%
JavaScript  ████████████████  100%
Frameworks  ░░░░░░░░░░░░░░░░    0%
```

Fonts from Google Fonts: **Bebas Neue** + **Inter**  
AI: Anthropic's Claude API *(optional, only for photo import)*

---

## FILE STRUCTURE

```
mylist.html        ← the entire app
README.md          ← you are here
```

That's it. That's the repo.

---

## ROADMAP

```diff
+ Drag to reorder tasks
+ Long-press context menu (change priority, move category)
+ Empty state improvements
+ Undo delete (brief toast window)
? Recurring tasks
? Multiple lists / profiles
? PWA / installable app
```

PRs welcome. Keep it simple. One file preferred.

---

## CONTRIBUTING

1. Fork it
2. Break it
3. Fix it better
4. Open a PR with a clear description of what changed and why

The aesthetic is intentional. Black backgrounds, Bebas Neue headings, no gradients, no rounded corners. If you're adding UI, make it match.

---

## PHILOSOPHY

Most task apps try to be platforms. They want your email, your subscription, your attention, your data.

MyList wants nothing. It's a file. You own it. You host it if you want. You delete it if you don't. It doesn't have opinions about your productivity system.

**Get the thing done. Close the tab. Live your life.**

---

<div align="center">

*Built with obsessive attention to simplicity.*

**[⬇ Download](./mylist.html)** · **[🐛 Issues](../../issues)** · **[⭐ Star if you use it](../../stargazers)**

</div>
