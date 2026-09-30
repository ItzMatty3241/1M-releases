# 1M -- Bullworth Academy Online

Online multiplayer for *Bully: Scholarship Edition*.

This repository only holds the release files. To play, download **`1MLauncher.exe`**
from the [latest release](../../releases/latest) -- nothing else.

## What you need

- Windows 10 or 11
- *Bully: Scholarship Edition* on **Steam**, owned on the Steam account you are signed
  into, with Steam running while you play

Other versions of the game, the Rockstar Games Launcher one included, do not work.

## Playing

1. Download `1MLauncher.exe` and double-click it, from any folder.
   Windows may say "Windows protected your PC": click **More info**, then **Run anyway**.
2. The launcher shows no window of its own. It finds your Steam copy of Bully (or asks
   you to select `Bully.exe`), updates 1M, prepares 1M's own copy of the game, picks the
   fastest way to the server from where you are, and starts the game.
   The first start takes a few minutes; later starts take seconds.
3. Press **PLAY** on the title menu.

Your Steam install is only ever read, never changed. 1M keeps its files and its copy of
the game in `%LOCALAPPDATA%\1M`, and the launcher keeps itself up to date.

## Options

Hold **Shift** while you double-click `1MLauncher.exe`: check your setup, restore your
own Bully save, back up your account, choose a different `Bully.exe`, clean up files an
older 1M left in your Bully folder, or uninstall 1M.

Back up your account before reinstalling Windows or moving to another PC: it is a single
file, and without it your character is gone.

## Something went wrong?

If the launcher cannot start the game it says why in a message box. For help, send:

- `%LOCALAPPDATA%\1M\launcher.log`
- `%LOCALAPPDATA%\1M\game\client.log`

## About the "Source code" downloads

GitHub adds "Source code (zip)" and "Source code (tar.gz)" to every release on its own.
They are archives of this repository, which holds only this README; 1M's source is not
published.

## Credits

1M runs Bully with [SilentPatch](https://github.com/CookiePLMonster/SilentPatchBully) by
Silent (co-developed by P3ti), loaded by the
[Ultimate ASI Loader](https://github.com/ThirteenAG/Ultimate-ASI-Loader), plus the Bully
Widescreen Fix from the [Widescreen Fixes Pack](https://github.com/ThirteenAG/WidescreenFixesPack),
both by ThirteenAG. All MIT licensed; their licenses ship with them. They are installed
into 1M's own copy of the game only.

1M is a fan project, not affiliated with or endorsed by Rockstar Games or Take-Two
Interactive. *Bully* is their trademark.
