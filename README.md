<p align="center">
  <img src="logo.png" width="128" alt="WinterSill logo">
</p>

<h1 align="center">WinterSill</h1>

<p align="center">
  Cozy snowfall on your Windows desktop.<br>
  Snow settles on your windows, slides off when you move them, and you can play with it.
</p>

<p align="center">
  <a href="https://apps.microsoft.com/detail/9P2195LJW7QQ">
    <img src="https://get.microsoft.com/images/en-us%20dark.svg" width="200" alt="Get it from Microsoft">
  </a>
</p>

<p align="center">
  or <a href="https://github.com/4Kcr/WinterSill/releases/latest">download it from GitHub</a>
</p>

## Contents

- [Features](#features)
- [Download and install](#download-and-install)
- [How to use](#how-to-use)
- [Start with Windows](#start-with-windows)
- [Updates](#updates)
- [Uninstall](#uninstall)
- [Privacy](#privacy)
- [License](#license)
- [Credits](#credits)

## Features

### Snow on your desktop

- Snow falls over the whole screen. Mouse clicks pass through it, so you can keep working as usual.
- Snow piles up on top of windows, on the taskbar and along the bottom of the screen. On Windows 11 it follows the rounded window corners.
- Drag a window and its snow rides along with it; move it quickly and some of the snow falls off. Close or minimize a window and its snow drops down.

### Play with the snow

- **Sweep:** move the cursor quickly through a snowdrift to throw the snow into the air.
- **Trails:** move the cursor slowly to leave a trail in the snow. Falling snow fills it in over time.
- **Snowman:** hold **Ctrl** and move the cursor through a snowdrift to roll a snowball. Release the key to drop it. Stack three snowballs to build a snowman with eyes, a smile, a carrot nose, buttons and twig arms. Its hat and scarf are chosen at random or set in the settings. The key can be changed to Shift or Alt.
- **Snowballs:** roll a small snowball, then flick the mouse and release the key to throw it. It leaves a splat that melts after a few seconds, or knocks a snowman over.

### Atmosphere

- **Weather:** the snow changes by itself between calm, normal, gusty and a short blizzard. Off by default.
- **Night mode:** the snow turns slightly bluer and dimmer. Automatic from 20:00 to 07:00 by default; can also be always on or off.
- **Frost:** frost patterns slowly grow in the screen corners and can be wiped off with the cursor. Off by default.
- **Garland:** a string of lights along the top of the screen, in multicolor, warm white or icy blue, twinkling, steady or as a running wave. Off by default.
- **Presets:** Standard, Quiet evening, Blizzard, Minimal and Festive change many settings at once.

### Stays out of your way

- **Full-screen apps:** snow hides while a game or video runs in full screen, including borderless full-screen windows. A game in an ordinary window with a title bar does not hide the snow.
- **Where it snows:** everywhere, only over the desktop and system windows (File Explorer, taskbar, Windows Settings, Task Manager), or everywhere except the apps you choose.
- **Multiple monitors:** snow can fall on all monitors or only on the main one.
- **Battery:** on battery power, WinterSill can keep running as usual, show lighter snow, or pause.
- **Hotkeys:** **Ctrl+Alt+F9** pauses the snow and **Ctrl+Alt+F10** clears it. Both can be changed or turned off.
- **Language:** the interface is in Russian when Windows uses Russian, and in English otherwise.

## Download and install

### Microsoft Store (recommended)

Get WinterSill from the [Microsoft Store](https://apps.microsoft.com/detail/9P2195LJW7QQ). The Store installs and updates it for you.

### GitHub

Go to [Releases](https://github.com/4Kcr/WinterSill/releases/latest) and download one of these files:

| File | What it is |
|---|---|
| `WinterSill-Setup-<version>.exe` | **Installer.** Installs for your user account only, without administrator rights. Adds a Start menu shortcut, optionally a desktop shortcut and start with Windows, and registers WinterSill in Windows Settings so it can be uninstalled there. |
| `WinterSill-<version>-portable.zip` | **Portable version.** Unzip it to any folder and run `WinterSill.exe`. Nothing is installed. |

These files are not signed with a code-signing certificate, so Windows SmartScreen may show **"Windows protected your PC"** the first time you run them. Click **More info**, then **Run anyway**.

### Requirements

- Windows 10 or Windows 11. WinterSill has been tested on Windows 11.
- The Microsoft Store version requires 64-bit Windows 10 version 1809 or newer.
- .NET Framework 4, which is already part of Windows 10 and Windows 11.

## How to use

While WinterSill is running, its icon sits in the notification area next to the clock.

- **Right-click** the icon for the menu: Settings, snow amount (Light, Medium, Heavy, Blizzard), Shake the snow loose, Clear all snow, Pause, Start with Windows (GitHub version only) and Exit.
- **Double-click** the icon to shake all the snow loose.
- **Settings** has six tabs: Snow, Drifts, Play, Atmosphere, Where and General. Changes apply immediately. **Reset to defaults** restores the original settings.
- Starting WinterSill again while it is already running opens its settings.

## Start with Windows

- **Microsoft Store version:** WinterSill starts with Windows after you run it for the first time. To turn this off, open Windows **Settings → Apps → Startup**.
- **GitHub version:** use the **Start with Windows** option in the installer, in the tray menu or in **Settings → General**.

## Updates

- **Microsoft Store version:** the Store updates WinterSill.
- **GitHub version:** about 30 seconds after starting, and then every 6 hours, WinterSill checks the [Releases](https://github.com/4Kcr/WinterSill/releases/latest) page for a newer version. If there is one, it shows a notification and adds a download item to the tray menu. Clicking either opens the release page in your browser; nothing is downloaded automatically. You can turn the check off or run it manually in **Settings → General**.
  - **Installer:** download the new installer and run it. Your settings are kept.
  - **Portable version:** exit WinterSill, then replace `WinterSill.exe` with the new one.

## Uninstall

- **Microsoft Store version:** Windows **Settings → Apps → Installed apps → WinterSill → Uninstall**.
- **Installer version:** Windows **Settings → Apps → Installed apps → WinterSill → Uninstall**. This removes the program, its shortcuts, its settings and its start-with-Windows entry.
- **Portable version:** turn off **Start with Windows** in WinterSill's settings, exit WinterSill and delete the file. Its settings stay in the Windows registry under `HKEY_CURRENT_USER\Software\WinterSill`; you can delete that key if you no longer need them.

## Privacy

- No ads, no account and no telemetry.
- To place the snow, WinterSill reads the position and size of open windows, their window class, and the name of the program each window belongs to. To recognise the Windows Settings window, it also reads the titles of windows that belong to Windows Store-style apps. WinterSill does not read what is inside windows.
- On the **Where** tab, the program list shows the titles of open windows, and **All programs…** reads the shortcuts in your Start menu and on your desktop to list installed programs. This happens only when you use these options.
- This information is used only on your computer and is not sent anywhere. Settings, including the list of programs you exclude, are stored in the Windows registry under `HKEY_CURRENT_USER\Software\WinterSill`.
- **GitHub version:** the only network connection is the update check, a request to the GitHub API (`api.github.com`). Like any web request, it reveals your IP address to GitHub. You can turn it off in **Settings → General**.
- **Microsoft Store version:** WinterSill itself makes no network connections. Updates are handled by the Microsoft Store.

## License

WinterSill is freeware: free for personal and commercial use, but not open source. The source code is not published. See [LICENSE](LICENSE) for the full terms.

## Credits

Created by [4Kcr](https://github.com/4Kcr), with coding help from Claude.

Inspired by desktop snow apps.
