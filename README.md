# MyList

A minimalist task management app that converts handwritten notes to digital tasks using AI.

![Pure black, monochromatic design](https://img.shields.io/badge/design-monochromatic-black)
![Single HTML file](https://img.shields.io/badge/file-single%20HTML-blue)
![No dependencies](https://img.shields.io/badge/dependencies-none-green)

---

## What It Does

MyList helps you organize tasks across categories with a clean, distraction-free interface. The standout feature is **photo import** — snap a picture of your handwritten to-do list and let AI convert it to organized digital tasks.

---

## Features

**Task Management**
- Swipe carousel navigation between categories
- Add, edit, and complete tasks inline
- Swipe left to delete completed tasks
- Priority levels (Urgent, High, Medium)
- Break tasks into steps/subtasks
- Create subgroups within categories

**Smart Organization**
- "Urgent" category automatically collects all urgent tasks from other categories
- Editable category names directly in the UI
- Add/remove categories as needed

**Photo Import**
- Upload photos of handwritten lists
- AI reads and extracts tasks automatically
- Review and edit before importing
- Assigns tasks to existing or new categories

**Data Portability**
- Export to JSON (full backup)
- Export to plain text (readable)
- Export to .ics (Apple/Google Calendar)
- Import from JSON backup

---

## Getting Started

### Option 1: Just Open It
Download `mylist-v21.html` and open it in any modern browser. That's it.

### Option 2: Use Templates
When you first open the app, choose "Use Templates" to start with sample categories and tasks to see how everything works.

### Option 3: Photo Import
1. Get a Claude API key from [console.anthropic.com](https://console.anthropic.com)
2. Click the "CAM" button in the top right
3. Paste your API key (stored locally, never sent anywhere except Anthropic)
4. Upload a photo of your handwritten list
5. Review the extracted tasks and import

---

## How Data Is Stored

All data stays **local** on your device:

| Item | Storage | Purpose |
|------|---------|---------|
| Tasks & Categories | localStorage | Your task data |
| API Key | localStorage | Claude API key for photo import |

Nothing is sent to any server (except the Claude API when you use photo import).

To clear your data:
1. Open DevTools (F12)
2. Go to Application → Local Storage
3. Delete the entries for this file

---

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| ← → | Navigate between categories |
| Esc | Close any open modal |
| Enter | Submit when typing in modals |

---

## Design Philosophy

- **Pure black** (#000) background
- **Monochromatic** — no colors, just white on black
- **No emoji icons** — text labels only
- **Bebas Neue** typography for bold, readable titles
- **No borders** — clean, minimal aesthetic
- **Mobile-first** with touch gestures

---

## Technical Details

- **Single HTML file** — no build process, no npm, no frameworks
- **~1,800 lines** of vanilla HTML, CSS, and JavaScript
- **Zero dependencies** (except Google Fonts)
- Works offline after first load
- Tested on Chrome, Safari, Firefox

---

## File Structure

```
mylist-v21.html    ← The entire app
README.md          ← You're reading it
```

Yes, really. It's all in one file.

---

## Roadmap

Future versions may include:
- Cloud sync across devices
- User accounts
- Sharing lists
- Native mobile apps

---

## License

MIT — do whatever you want with it.

---

## Author

Built by [Your Name]

---

*If you find this useful, consider starring the repo.*
