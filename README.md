# Custom SVG taskbar icons for Telegram for KDE-Breeze

### Example. KDE, Breeze Dark
![muted chats](example/muted_chats.png "Muted chats")
![unmuted chats](example/unmuted_chats.png "Unmuted chats")

### Installation
1. `git clone https://github.com/D35YNC/tg-tray-icons.git`
2. `cd tg-tray-icons/%KDE-THEME-NAME%`
3. `sudo mv telegram-* /usr/share/icons/%KDE-THEME-NAME%/status/64/`
4. Make sure that no other icons exist in `/usr/share/icons/.../status/*` (`find . -name telegram*.svg`) If they exist, make a backup and delete them.
6. restart KDE session
