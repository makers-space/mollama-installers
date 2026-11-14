# Mollama installers

Downloads for the Mollama desktop app. This repository holds only the installers; the files for each version are attached to its [release](https://github.com/makers-space/mollama-installers/releases).

The links below always give the newest version.

| System | Download |
|---|---|
| Windows | [Mollama-Setup.exe](https://github.com/makers-space/mollama-installers/releases/latest/download/Mollama-Setup.exe) |
| macOS (Apple and Intel) | [Mollama.dmg](https://github.com/makers-space/mollama-installers/releases/latest/download/Mollama.dmg) |
| Linux | [Mollama.AppImage](https://github.com/makers-space/mollama-installers/releases/latest/download/Mollama.AppImage) |

The installers are not signed yet, so each system warns before opening them. The steps below get past the warning.

## Windows

1. Download `Mollama-Setup.exe` and run it.
2. If Windows shows "Windows protected your PC", choose **More info**, then **Run anyway**.

On a computer with Smart App Control turned on, Windows refuses unsigned apps and offers no way past. The app cannot be installed there until the installer is signed.

## macOS

1. Download `Mollama.dmg`, open it, and drag Mollama into Applications.
2. The first time, right-click Mollama in Applications and choose **Open**, then **Open** again. If macOS still refuses, go to **System Settings → Privacy & Security** and choose **Open Anyway**.

## Linux

1. Download `Mollama.AppImage`.
2. Allow it to run as a program: in the file's Properties, or with `chmod +x Mollama.AppImage`.
3. Open it.

## After installing

Open Mollama and sign in. That computer is linked to your account, appears on the Devices page, and its models can then be used from any of your Mollama apps.

Models run through [Ollama](https://ollama.com), which needs to be installed on the same computer.
