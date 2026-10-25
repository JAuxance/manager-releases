<p align="center">
  <a href="https://getmanager.app">
    <img src=".github/assets/banner.png" alt="Manager" width="100%">
  </a>
</p>

<p align="center">
  <a href="../../releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/JAuxance/manager-releases?style=flat-square&label=release&labelColor=000000&color=262626"></a>
  <a href="../../releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/JAuxance/manager-releases/total?style=flat-square&label=downloads&labelColor=000000&color=262626"></a>
  <img alt="Windows · Linux" src="https://img.shields.io/badge/platform-Windows%20%C2%B7%20Linux-262626?style=flat-square&labelColor=000000">
  <img alt="Free" src="https://img.shields.io/badge/price-free-262626?style=flat-square&labelColor=000000">
</p>

<p align="center">
  <a href="https://getmanager.app"><b>getmanager.app</b></a>
  &nbsp;·&nbsp;
  <a href="../../releases/latest">Download</a>
  &nbsp;·&nbsp;
  <a href="https://getmanager.app/tour">Tour</a>
</p>

<br>

Official binary releases of **Manager**, a desktop app for focus, discipline and long-term consistency.

## Download

| Platform | Package | |
|---|---|---|
| **Windows** | `.exe` installer | [Latest release →](../../releases/latest) |
| **Debian / Ubuntu** | `.deb` | [Latest release →](../../releases/latest) |
| **Arch Linux** | AUR · `manager-bin` | `yay -S manager-bin` |

Once installed, Manager updates itself: new versions are signed and verified before they install.

## Inside

<table>
  <tr>
    <td width="33%" valign="top">
      <img src=".github/assets/view-1.png" alt="Today" width="100%"><br>
      <sub>The day on one screen. Every day you hold adds a mark to the streak.</sub>
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/view-2.png" alt="Tasks" width="100%"><br>
      <sub>One list per day, three priorities. Daily tasks repeat on their own.</sub>
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/view-3.png" alt="Focus" width="100%"><br>
      <sub>Pomodoro, Deep Work, Sprint, Flow or your own. Always-on-top widget.</sub>
    </td>
  </tr>
  <tr>
    <td width="33%" valign="top">
      <img src=".github/assets/view-4.png" alt="Schedule" width="100%"><br>
      <sub>Your usual week in slots, checked in on the day.</sub>
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/view-5.png" alt="Journal" width="100%"><br>
      <sub>A few lines at night and a mood. What held, what slipped.</sub>
    </td>
    <td width="33%" valign="top">
      <img src=".github/assets/view-6.png" alt="Review" width="100%"><br>
      <sub>7, 30 or 90 days: focus time, tasks done, days held, sleep.</sub>
    </td>
  </tr>
</table>

**Dona**, the AI coach, is built in: bring your own key or subscribe to Dona Plus.
Your data stays in a local file on your machine; sync is optional.

<p align="center">
  <img src=".github/assets/today.png" alt="Manager — Today view" width="100%">
</p>

## Installation

<details>
<summary><b>Windows</b></summary>
<br>

Download `Manager_x.x.x_x64-setup.exe` from the [latest release](../../releases/latest) and run it.

</details>

<details>
<summary><b>Debian / Ubuntu</b></summary>
<br>

Download `Manager_x.x.x_amd64.deb` from the [latest release](../../releases/latest), then:

```bash
sudo apt install ./Manager_x.x.x_amd64.deb
```

</details>

<details>
<summary><b>Arch Linux (AUR)</b></summary>
<br>

```bash
yay -S manager-bin
```

The AUR package is community-maintained and may lag a few versions behind.

</details>

## Requirements

| Platform | Dependencies |
|---|---|
| Windows | None (self-contained installer) |
| Debian / Ubuntu | `libwebkit2gtk-4.1`, `libgtk-3-0`, `libayatana-appindicator3-1` |
| Arch Linux | `webkit2gtk-4.1`, `gtk3`, `libayatana-appindicator` |

## License

© 2026 JAuxance. All rights reserved.
This software is proprietary. Redistribution or modification is not permitted without prior written consent.
