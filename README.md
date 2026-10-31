# Screen Tools — releases

Signed and notarized builds of **Screen Tools**, a macOS menu-bar app with Windows habits and display helpers:

- **Window snapping:** ⌘ + arrows snap to a grid you choose.
- **PC keyboard habits:** Alt-Tab, Ctrl-C/X/V/Z, Ctrl-arrows by word, Home/End to the start and end of the line, and Alt-Shift to switch language.
- **Brightness:** a slider for each screen.
- **Big Clock and pre-lock warning:** the Big Clock screen saver, with a warning before the screen locks.
- **Mouse:** pointer and wheel speed for each mouse, and hold the wheel to scroll.
- **Window layouts:** remembered for each monitor setup.

This repository holds only the release builds; the source is private.

## Install

1. Download `ScreenTools-<version>.zip` from the [latest release](https://github.com/gitayg/screentools-releases/releases/latest) and unzip it.
2. Move **Screen Tools.app** to `~/Applications` or `/Applications`, then open it. It appears in the menu bar.
3. When asked, allow Screen Tools in **System Settings › Privacy & Security › Accessibility**. The keyboard and window features need it.

Requires macOS 14 or later.

## Updates

Screen Tools checks this repository when it starts and every six hours. When there's a newer release, it installs it and relaunches.

It installs only a build signed with its developer's Developer ID (team `DA4PX65QXV`) for its own bundle ID (`com.itayglick.screentools`). To choose when to update, turn off **Install Updates Automatically** in the menu.
