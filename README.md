# Discord Folder Icons Theme

<img width="109" height="261" alt="image" src="https://github.com/user-attachments/assets/1c32fbaa-262d-4b69-a4d7-1835ce7d69d9" />


A small Discord theme to change the server folders to a custom emoji icon.

<br>

## Installation

I only tested it with Vencord, but it should work with any client that supports theme files, like BetterDiscord.
1. Download the [theme file](https://github.com/DoppelKomma/discord-folder-icons-theme/blob/main/folder-icons.theme.css) — click the  `↓` `(Download raw file)` button in the top right of the file view.
2. Move it into your theme folder.
	- For Vencord go to: Discord -> Settings -> Themes -> Open Themes Folder

Alternativly you can copy the content of [folder-icon.themes.css](https://github.com/DoppelKomma/discord-folder-icons-theme/blob/main/folder-icons.theme.css) and add it to quick css, but make sure the `@import` is at the top of the file.

## Setup

Open the `folder-icons.theme.css` file and edit the `FOLDERS` section:

### Per-folder config

- One line per folder
- Replace Folder Name with your exact folder name
```css
/* ══════════════════════════════════════════════
   FOLDERS — one line per folder
   ══════════════════════════════════════════════ */
[data-dnd-name="Folder name"]	{ --icon: '❤️'; }
[data-dnd-name="Games"]			{ --icon: '🎮'; }
```
You can change the background color in Discord. **If it's set to default, the background will be transparent**.

### Additional settings:

To change emoji size, corner rounding and badge border:
```css
/* ══════════════════════════════════════════════
   ADDITIONAL SETTINGS
   ══════════════════════════════════════════════ */
:root {
  --folder-emoji-size: 30px;    /* emoji size */
  --folder-radius:     16px;    /* background corner rounding (default 16px) */
  --badge-border:      2px;     /* ring thickness around red unread counter (default 2px) */
  --open-icon:         none;    /* none = discord default open folder, remove to keep custom icon or set custom open emoji like '📂' */
}
```
