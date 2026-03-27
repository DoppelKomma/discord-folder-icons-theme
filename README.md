# Discord Folder Icon Theme

<img width="62" height="207" alt="image" src="https://github.com/user-attachments/assets/bfca404d-d683-4dd8-bdc3-ac7ca4ac61a8" />
A small Discord theme to change the server folders to a custom emoji icon and color.



## Installation

I only tested it with Vencord, but it should work with any client that supports theme files.
1. [Download the theme file](https://github.com/DoppelKomma/discord-folder-icons-theme/blob/main/folder-icons.theme.css).
2. Paste or drag it into your theme folder.


## Setup

Open the `folder-icons.theme.css` file and edit the two sections at the top:
### Per-folder config - one line per folder, use your exact folder name:
```css
[data-dnd-name="My Folder"] { --icon: '🎮'; --color: #b4977c; }
```

### Aditional settings:
```css
:root {
    --folder-radius: 16px;       /* corner rounding */
    --folder-emoji-size: 30px;   /* emoji size */
    --badge-border: 2px;         /* red unread counter ring thickness */
}
```
