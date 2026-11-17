# Mollama installers

Downloads for the Mollama desktop app. This repository holds only the installers; the files for each version are attached to its [release](https://github.com/mkrspc-one/mollama-installers/releases).

The links below always give the newest version.

| System | Download |
|---|---|
| Windows | [Mollama-Setup.exe](https://github.com/mkrspc-one/mollama-installers/releases/latest/download/Mollama-Setup.exe) |
| macOS (Apple and Intel) | [Mollama.dmg](https://github.com/mkrspc-one/mollama-installers/releases/latest/download/Mollama.dmg) |
| Linux | [Mollama.AppImage](https://github.com/mkrspc-one/mollama-installers/releases/latest/download/Mollama.AppImage) |

The installers are not signed yet, so each system warns before opening them. The steps below get past the warning.

## Windows

1. Download `Mollama-Setup.exe` and run it.
2. If Windows shows "Windows protected your PC", choose **More info**, then **Run anyway**.

On a computer with Smart App Control turned on, Windows refuses unsigned apps and offers no way past. The app cannot be installed there until the installer is signed.

## macOS

1. Download `Mollama.dmg`, open it, and drag Mollama into Applications.
2. Open Mollama. macOS refuses the first time.
   - If it says the app **cannot be checked for malicious software**, or is from an unidentified developer: open **System Settings → Privacy & Security**, scroll down, and choose **Open Anyway**.
   - If it says the app **is damaged and can't be opened**: the app is not damaged; this is how macOS reports an unsigned app. Open Terminal, run `xattr -cr /Applications/Mollama.app`, then open Mollama again.

## Linux

1. Download `Mollama.AppImage`.
2. Allow it to run as a program: in the file's Properties, or with `chmod +x Mollama.AppImage`.
3. Open it.

## After installing

Open Mollama and sign in. That computer is linked to your account, appears on the Devices page, and its models can then be used from any of your Mollama apps.

Models run through [Ollama](https://ollama.com), which needs to be installed on the same computer.

## Staging build

For testing. "Mollama Staging" is the same app, but it opens the staging site, which only administrators can sign in to. It installs beside the normal app and keeps its own sign-in. The same steps apply, with `Mollama Staging` in place of `Mollama` in the file and app names.

| System | Download |
|---|---|
| Windows | [Mollama-Staging-Setup.exe](https://github.com/mkrspc-one/mollama-installers/releases/latest/download/Mollama-Staging-Setup.exe) |
| macOS (Apple and Intel) | [Mollama-Staging.dmg](https://github.com/mkrspc-one/mollama-installers/releases/latest/download/Mollama-Staging.dmg) |
| Linux | [Mollama-Staging.AppImage](https://github.com/mkrspc-one/mollama-installers/releases/latest/download/Mollama-Staging.AppImage) |
