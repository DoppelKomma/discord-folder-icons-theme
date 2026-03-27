# Discord Folder Icon Theme
Discord theme to replace the default server folder look with custom emojis.

<img width="62" height="207" alt="image" src="https://github.com/user-attachments/assets/bfca404d-d683-4dd8-bdc3-ac7ca4ac61a8" />

---

## Setup

Open the `.css` file and edit the two sections at the top:

**Global settings** — applies to all folders:
```css
:root {
    --folder-radius: 16px;       /* corner rounding (50% for circles) */
    --folder-emoji-size: 30px;   /* emoji size inside the icon */
    --badge-border: 2px;         /* red unread counter ring thickness */
}
```

**Per-folder config** — one line per folder, use your exact folder name:
```css
[data-dnd-name="My Folder"] { --icon: '🎮'; --color: #b4977c; }
```
