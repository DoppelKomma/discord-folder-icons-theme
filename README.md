# Discord Folder Icon Theme

<img width="109" height="261" alt="image" src="https://github.com/user-attachments/assets/1c32fbaa-262d-4b69-a4d7-1835ce7d69d9" />


A small Discord theme to change the server folders to a custom emoji icon and color.

<br>

## Installation

I only tested it with Vencord, but it should work with any client that supports theme files.
1. Download the [theme file](https://github.com/DoppelKomma/discord-folder-icons-theme/blob/main/folder-icons.theme.css) — click the **download button** (↓) in the top right of the file view.
2. Move it into your theme folder.
	- For Vencord go to: Discord -> Settings -> Themes -> Open Themes Folder



## Setup

Open the `folder-icons.theme.css` file and edit the FOLDERS section:


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


### Additional settings:

To change emoji size, corner rounding and badge border:
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
