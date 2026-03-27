# Discord Folder Icon Theme

<img width="62" height="207" alt="image" src="https://github.com/user-attachments/assets/bfca404d-d683-4dd8-bdc3-ac7ca4ac61a8" />

A small Discord theme to change the server folders to a custom emoji icon and color.



## Installation

I only tested it with Vencord, but it should work with any client that supports theme files.
1. [Download the theme file](https://github.com/DoppelKomma/discord-folder-icons-theme/blob/main/folder-icons.theme.css). (Download button on the top right)
2. Move it into your theme folder.



## Setup

Open the `folder-icons.theme.css` file and edit the the FOLDERS section:


### Per-folder config

- One line per folder
- Replace Folder Name with your exact folder name
- Customize the icon and background color
```css
/* ══════════════════════════════════════════════
   FOLDERS — one line per folder
   ══════════════════════════════════════════════ */
[data-dnd-name="My Folder"]	{ --icon: '❤️'; --color: #8578b4; }
[data-dnd-name="Games"]		{ --icon: '🎮'; --color: #b4977c; }
```


### Aditional settings:

To change emoji size:
```css
/* ══════════════════════════════════════════════
   ADDITIONAL SETTINGS
   ══════════════════════════════════════════════ */
:root {
    --folder-emoji-size: 30px;   /* emoji size */
    --folder-radius: 16px;       /* corner rounding */
    --badge-border: 2px;         /* red unread counter ring thickness */
}
```
