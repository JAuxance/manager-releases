# Manager — Binary Releases

This repository hosts the official binary releases of **Manager**, a desktop productivity app built for focus, discipline, and long-term consistency.

## Features

- Day counter & streak tracking
- Daily task management with priorities
- Weekly schedule planner
- Pomodoro-style focus timer with always-on-top widget
- Daily journal
- Progress charts
- AI coach (bring your own key or subscribe to Dona Plus)

## Installation

### Arch Linux (via AUR)

```bash
yay -S manager-bin
```

### Debian / Ubuntu

Download the latest `.deb` from the [Releases](../../releases/latest) page and install:

```bash
sudo dpkg -i Manager_x.x.x_amd64.deb
```

### Windows

Download the `.exe` installer from the [Releases](../../releases/latest) page.

## Requirements

| Platform | Dependencies |
|----------|-------------|
| Arch Linux | `webkit2gtk-4.1`, `gtk3`, `libayatana-appindicator` |
| Debian/Ubuntu | `libwebkit2gtk-4.1`, `libgtk-3-0`, `libayatana-appindicator3-1` |
| Windows | None (self-contained installer) |

## License

© 2026 JAuxance. All rights reserved.  
This software is proprietary. Redistribution or modification is not permitted without prior written consent.
