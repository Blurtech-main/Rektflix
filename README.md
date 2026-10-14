# Rektflix

Rektflix is a self-contained Windows recorder and World of Warcraft Classic addon. It continuously records the selected WoW window into a rolling buffer, allowing you to save recent gameplay or automatically capture selected events without OBS.

## Getting started

1. Download and extract the complete Rektflix ZIP. Do not run it from inside the ZIP.
2. Open `Rektflix.exe`.
3. Confirm the detected WoW Forever folder, or select the `_classic_beta_` folder containing `WowB.exe`.
4. Select **Install / update addon**, then restart WoW after the first installation.
5. Open WoW and confirm that Rektflix displays **BUFFER RECORDING**.
6. Type `/rf` in WoW to open the addon controls.
7. Create and play one test clip before relying on automatic triggers.

No OBS installation, account, cloud service, game injection, or automated keypresses are required.

## Main features

- Disk-backed rolling video buffer lasting from 1 minute to 5 hours.
- Save-recent buttons with user-selected clip lengths.
- Separate manual recording controls.
- Automatic clips for selected PvP, death, spell, interrupt, creature, and watched-item events.
- Adjustable before-event and after-event clip durations.
- H.264 video with optional system audio and microphone recording.
- Resolutions from 640×360 through 3840×2160, at 15–60 FPS.
- Draggable in-game control bar, settings panel, help manual, and PvP history.
- Recovery of usable buffered footage after an interrupted recorder session.
- Local-only clips and settings; Rektflix does not upload your recordings.

## Disk Space Clearer

The optional Disk Space Clearer scans a selected drive and presents the largest results as understandable collections. Nested subfolders contribute to their nearest qualifying collection, while the same file is never listed twice.

Collections can be expanded to review up to 100 files. You may move only selected large files or choose an entire folder. Programs and installers are kept with their related folder files to reduce the chance of separating dependencies.

Before moving anything, Rektflix shows the destination, required capacity, and expected space recovered. Each file is copied to a temporary name, flushed, SHA-256 verified, safely renamed without overwriting an existing file, and only then removed from its original location. Interrupted moves can be resumed from their restoration manifest.

## Files and privacy

- Saved clips default to `Videos\Rektflix`.
- Settings, rolling-buffer fragments, and diagnostics are stored in `%LOCALAPPDATA%\Rektflix`.
- Rektflix does not upload video or require an online account.
- System-audio recording can include voice chat, notifications, and any other sound playing through the selected device.
- Saved clips are never automatically deleted.

## Troubleshooting

- **WAITING FOR WOW:** Select the `_classic_beta_` folder containing `WowB.exe`, then restore the game window.
- **No automatic clips:** Confirm that fresh combat-log activity appears in the Windows app. In WoW, try `/combatlog`.
- **No in-game controls:** Restart WoW after installing the addon, then type `/rf`.
- **Black or stalled capture:** Use borderless or windowed mode, restore the WoW window, update the graphics driver, or try software encoding at a lower resolution and frame rate.
- **No system sound:** Select the correct Windows default playback device, then disarm and rearm recording.
- **More diagnostic information:** Open **Diagnostics** in Rektflix to locate `diagnostics.txt` and `state.json`.

## Sharing

Share an individual `.mp4` to share a clip. To let somebody record their own gameplay, share the complete Rektflix ZIP. Windows may display an unsigned-application warning because this preview does not use a paid code-signing certificate.

