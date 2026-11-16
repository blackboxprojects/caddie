<p align="center"><img src="docs/icon.png" width="128" alt="Caddie icon"></p>

<h1 align="center">Caddie</h1>

<p align="center">One menu bar app for your Mac, many small tools.</p>

<p align="center">
  <a href="https://github.com/blackboxprojects/caddie/releases/latest/download/Caddie.dmg"><b>⬇ Download Caddie for macOS</b></a><br>
  <sub>Free · macOS 14 or later · Apple silicon</sub>
</p>

Caddie replaces a drawer full of single-purpose utilities with one app in your menu bar. A dock, a menu bar tidier, clipboard history, screenshots, a window switcher, a security monitor, an app uninstaller and more, all in one place. Every feature starts switched off: turn on the ones you want and leave the rest alone.

<p align="center"><img src="docs/settings.png" width="760" alt="Caddie's Settings window: the sidebar lists features grouped under Layout, Utilities, Productivity and Housekeeping, each switched on, with the Menu Bar page open on the right"></p>

## Features

### Layout
- **Desktop & Dock:** a replacement dock with window previews, on any screen edge or display. It can hide Apple's Dock and puts it back when you turn the option off.
- **Menu Bar:** tucks menu bar icons behind an arrow until you need them. Sort icons into Shown, Hidden and Always Hidden, and pick the arrow's look and the spacing between icons.

### Utilities
- **Monitor:** a panel under the Caddie icon showing network traffic by app, CPU, memory, disk, battery and temperature, with alerts like "CPU above 90% for 5 minutes."
- **Security:** a score out of 100 for this Mac's protections (FileVault, firewall, Gatekeeper and more). It also lists what starts at login, plus extensions and certificates, and alerts you when they change. When macOS blocks an app, you can allow just that app here instead of digging through System Settings. Powered by [osquery](https://osquery.io), built into Caddie, so there's nothing extra to install.
- **Screenshot:** capture an area, a window or a whole screen, including scrolling captures. Then annotate, pin the shot on screen, or copy it.
- **World Clock:** every city you care about side by side, with a strip of hours to find a meeting time at a glance.
- **Web Browser:** sends each link to the right browser, based on the app you clicked it in, the site, or both. Hold ⌥ Option while clicking a link to pick a browser.
- **Power Actions:** extra Finder right-click actions, like new file here, copy path, open in Terminal, and move to or copy to your favourite folders.
- **Cleaning Mode:** locks the keyboard and blacks out the screen while you wipe them down.

### Productivity
- **Clipboard:** a history of text, links, images and files you copy. Hold ⌘ after ⌘V to search and paste anything from it. Nothing leaves your Mac.
- **Action Panel:** one shortcut opens a grid of your favourite actions, each on its own key.

### Housekeeping
- **App Manager:** drop an app in to uninstall it along with the files it left behind. The Updates tab lists Homebrew and App Store apps with new versions and can upgrade Homebrew apps by itself.
- **System Cleaner:** finds caches, logs, leftovers from removed apps and other space you can get back. You choose what goes, and it goes to the Trash.

### Keyboard
- **Keyboard Shortcuts:** turn Caps Lock (or another key) into a master key, or double-tap a modifier, to open apps, links, files or any Caddie action.
- **Window Switcher:** ⌘Tab through every window, not just apps. ⌘` switches between the windows of the app in front. Both shortcuts can be changed.

### And
- **Updates itself** from this page's releases. Each update is checked to be signed by the same developer before it's installed.
- **Permissions page:** shows which macOS permissions Caddie has and which features need them, with a button to allow each one.
- **Private:** no account, no analytics. The network is used only to check for updates, and by the features you turn on that need it (like App Manager asking Homebrew for updates).

## Install

1. [Download Caddie.dmg](https://github.com/blackboxprojects/caddie/releases/latest/download/Caddie.dmg) and open it.
2. Drag **Caddie** onto the **Applications** shortcut, then open it from Applications. Caddie appears in your menu bar and opens its Settings.
3. **First launch:** Caddie isn't notarized by Apple, so macOS blocks it the first time. Click **Done**, then open **System Settings → Privacy & Security**, scroll to the message about Caddie, click **Open Anyway**, and confirm. You only do this once.

Turn on the features you want in Settings. If a feature needs a permission, such as Accessibility or Screen Recording, Caddie says which one and has a button to allow it.

## Updates

Caddie keeps itself up to date (Settings → General → App updates). Automatic updates are on by default; switch them off to check and install by hand. Older versions and release notes are on the [Releases](https://github.com/blackboxprojects/caddie/releases) page.

## Requirements

A Mac with Apple silicon (M1 or later) running macOS 14 Sonoma or later.

## Support

If Caddie saves you a few apps, you can buy me a coffee:

<a href="https://www.buymeacoffee.com/blackboxlabs"><img src="https://img.buymeacoffee.com/button-api/?text=Buy%20me%20a%20coffee&emoji=&slug=blackboxlabs&button_colour=FFDD00&font_colour=000000&font_family=Cookie&outline_colour=000000&coffee_colour=ffffff" alt="Buy me a coffee" height="48"></a>

## Credits

Caddie includes [osquery](https://github.com/osquery/osquery) (Apache 2.0) and uses [DB-IP](https://db-ip.com) country data (CC BY 4.0) for Monitor's network view.
