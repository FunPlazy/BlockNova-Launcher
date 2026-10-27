# BlockNova Launcher

A modern, free Minecraft: Java Edition launcher for Windows.
Every version, every mod loader, your own skin and modpacks in one click.

## Features

- **Every version** – releases, snapshots, Beta, Alpha, Infdev, Classic and the very first `rd-132211` (2009).
- **One PLAY button** – the game, libraries, assets and the right Java runtime (8 / 17 / 21+) are downloaded automatically.
- **Accounts**
  - **Microsoft** – official sign-in; nickname and skin stay in sync with the official launcher.
  - **Ely.by** – free accounts with skins (authlib-injector is downloaded automatically).
  - **Offline** – just a nickname.
- **Skins**
  - 3D preview with animations (idle / walk / run / fly), Steve and Alex models, drag-and-drop PNG.
  - Premium accounts: upload straight to your Minecraft profile.
  - Offline accounts: your skin is visible in game. 1.7.2+ uses a built-in local skin server for authlib-injector; older versions use an auto-generated resource pack.
  - Grab any premium player's skin by nickname, plus a skin library with import from the official launcher.
- **Nickname change** – Microsoft (with availability check and the 30-day rule), offline (instant), Ely.by.
- **Modpacks**
  - Unlimited instances, each with its own folder (mods, worlds, configs, settings).
  - Each instance has its own game version and loader: **Fabric, Quilt, Forge, NeoForge**.
- **Modrinth & CurseForge**
  - Search and install mods (required dependencies included) and complete modpacks (`.mrpack` and CurseForge `manifest.json`).
  - Or drag in your own `.jar` files and enable or disable mods with a toggle.
- **Look & feel** – animated pixel-art landscape, "Minecraft Eras" timeline, 6 accent themes, custom launcher background, custom icons and covers for modpacks.
- **Installer** – Windows setup with optional desktop shortcut and taskbar pin, or a portable `.exe`.

## Download

Get the latest `BlockNova-Setup.exe` (installer) or `BlockNova-Portable.exe` from **[Releases](../../releases)**.

> Windows SmartScreen may warn about an unknown publisher (the build is not code-signed). Click **More info → Run anyway**.

## Build from source

Requires Node.js 20+.

    npm install
    npm start        # run the launcher
    npm run dist     # build installer + portable exe into dist/

## Where files live

- Game files (versions, worlds, mods): `%APPDATA%\.blocknova` (can be changed in Settings).
- Launcher settings and accounts: `%APPDATA%\BlockNova Launcher`.

## Disclaimer

BlockNova is not an official Minecraft product. Not approved by or associated with Mojang or Microsoft.
