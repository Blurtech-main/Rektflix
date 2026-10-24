# 🎬 Rektflix

<p align="center">
  <img src="./0fd7f93c-d347-49e8-8ee1-b6b9bd1ee455.png" alt="Rektflix Logo" width="650">
</p>

**Clip the chaos. Keep the kill-log. Reclaim your disk space.** 🎮💾

## Authoritative Windows release

The authoritative Windows download is [Rektflix-Windows.zip from the `Release` GitHub release](https://github.com/Blurtech-main/Rektflix/releases/download/Release/Rektflix-Windows.zip).

- Release version: **v0.1.4** (red-R icon refresh; rolling `Release` GitHub release)
- Package size and SHA-256: published alongside the rolling [Release asset](https://github.com/Blurtech-main/Rektflix/releases/tag/Release)
- Included executable: `Rektflix.exe` **0.1.4.0**, product version `0.1.4-disk-space-clearer`
- Visual identity: professional red `R` on black for the EXE, title bars, taskbar, and tray.

The copy named `Rektflix-Windows.zip` in the repository is the same complete package published on the rolling `Release` page. Verify its SHA-256 before extracting it.

## Getting started

Rektflix is a self-contained **Windows recorder and World of Warcraft Classic / Forever Beta addon**. It continuously records the selected WoW window into a rolling buffer, so you can save recent gameplay or automatically capture selected events **without OBS**. That ridiculous moment from three minutes ago? It doesn't have to live only in your memory. 💀

And it's not just a recorder: **Disk Space Clearer** is a substantial, built-in file-management feature for finding what's eating your storage and carefully moving it somewhere with more room. 🧹

## 🚀 Getting started

1. Download and extract the **complete Rektflix ZIP**. Do **not** run it from inside the ZIP. 📦
2. Open `Rektflix.exe`.
3. Confirm the detected WoW Forever folder, or select the `_classic_beta_` folder containing `WowB.exe`.
4. Select **Install / update addon**, then restart WoW after the first installation.
5. Open WoW and confirm that Rektflix displays **BUFFER RECORDING**. 🔴
6. Type `/rf` in WoW to open the addon controls.
7. **Create and play one test clip** before relying on automatic triggers. Future-you will be grateful.

No OBS installation, account, cloud service, game injection, or automated keypresses are required. Just the application, the addon, and your questionable decision to pull three more mobs. 🐉

## ✨ Main features

- 🔁 **Rolling video buffer:** disk-backed recording from **1 minute to 5 hours**.
- ⏪ **Save recent gameplay:** buttons with user-selected clip lengths.
- 🎬 **Manual recording:** separate controls when you want to be the director.
- ⚔️ **Automatic event clips:** selected PvP, death, spell, interrupt, creature, and watched-item events.
- ⏱️ **Adjustable event timing:** set how much footage to keep before and after an event.
- 🎥 **Video and audio:** H.264, with optional system audio and microphone recording.
- 🖥️ **Capture settings:** **640×360 to 3840×2160** at **15–60 FPS**.
- 🕹️ **In-game interface:** draggable control bar, settings panel, help manual, and PvP history.
- 🧯 **Recorder recovery:** recover usable buffered footage after an interrupted recorder session.
- 🔒 **Local-first:** clips and settings stay local; Rektflix does **not** upload your recordings.
- 💾 **Disk Space Clearer:** a fully developed storage-scanning and verified file-moving tool, described below. Yes, it has its own main-character arc.

---

## ![Disk Space Clearer — ROYGBIV heading](assets/disk-space-clearer-roygbiv.svg)

The optional **Disk Space Clearer** helps you figure out *where your storage went* and move large files or folders to a destination with more room. It is a proper, reviewable file-moving workflow🕵️‍♂️

### 🔍 Find the real space hogs

- **Scan a drive you choose** and see the largest results grouped into understandable, natural language **collections**.
- **Nested subfolders** contribute to their **nearest qualifying collection**, making the results easier to understand.
- **No double-counting:** the same file is never listed twice.
- **Expand a collection** to inspect up to **100 files** before deciding what to do.

### 🎛️ Move only what you choose

- Pick **individual large files** or move **an entire folder**.
- **Programs and installers stay grouped** with related folder files to reduce the risk of separating dependencies.
- Before anything moves, Rektflix previews the **destination**, **required destination capacity**, and **expected space recovered**. 🤹

### 🛡️ Carefully verified moves, not YOLO file transfers

For **each file**, Rektflix follows a deliberate sequence:

1. 📋 **Copy** to a temporary filename at the destination.
2. 💽 **Flush** the copied data.
3. 🔐 **Verify SHA-256** to confirm the destination copy matches.
4. ✅ **Rename safely**, without overwriting an existing file.
5. 🧹 **Remove the original only after** those steps have succeeded.

If a move is interrupted, it can be **resumed using its restoration manifest**. Because “power cut at 99%” should not be the final boss. ⚡

---

## 🛡️ Legitimate software 🕶️

Rektflix is designed as a **gameplay recorder, companion addon, and disk-management utility**—**not** a bot, cheat, or anti-cheat bypass. It does **not** inject code into the WoW process or send automated keypresses. It does not require cracked game files or include game-code bypasses. Its purpose is to **record what happens**, not play the game for you.

## 🔒 Files and privacy

- 📁 Saved clips default to `Videos\Rektflix`.
- ⚙️ Settings, rolling-buffer fragments, and diagnostics are stored in `%LOCALAPPDATA%\Rektflix`.
- ☁️🚫 Rektflix does **not** upload video or require an online account.
- 🔊 System-audio recording can include **voice chat, notifications, and any other sound** playing through the selected device. Check before sharing. 👀
- 🗃️ Saved clips are **never automatically deleted**.

## 🧰 Troubleshooting

- **⏳ WAITING FOR WOW:** Select the `_classic_beta_` folder containing `WowB.exe`, then restore the game window.
- **🎯 No automatic clips:** Confirm that fresh combat-log activity appears in the Windows app. In WoW, try `/combatlog`.
- **🕹️ No in-game controls:** Restart WoW after installing the addon, then type `/rf`.
- **⬛ Black or stalled capture:** Use borderless or windowed mode, restore the WoW window, update the graphics driver, or try software encoding at a lower resolution and frame rate.
- **🔇 No system sound:** Select the correct Windows default playback device, then disarm and rearm recording.
- **🔬 Need more diagnostic information?** Open **Diagnostics** in Rektflix to locate `diagnostics.txt` and `state.json`.

> [!NOTE]
> **🧪 WoW Forever Beta compatibility:** Rektflix **should work with WoW Forever Beta**, including the `_classic_beta_` setup using `WowB.exe`, but **it has not yet been tested on WoW**. Make a test clip and verify automatic triggers before trusting it with your greatest gaming achievement. Feel free to leave a comment (under Issues) if you notice any bugs or have any feature requests.


## 📦 Sharing

Share an individual `.mp4` to share a clip. To let somebody record their own gameplay, share the **complete Rektflix ZIP**.

Windows may display an **unsigned-application warning** because this preview does **not** use a paid code-signing certificate. That warning alone does not mean the app is malicious

## Testing status

The Windows package and automated application tests have been inspected and qualified. That package inspection does not constitute live Windows end-to-end acceptance or in-game testing. WoW Forever Beta compatibility remains **untested on WoW**, including addon loading and automatic trigger behavior; make a test clip and verify those behaviors before relying on them.

## 📝 Patch notes — 2026-10-21

Since the previous published package, Rektflix has gained a full **Disk Space Clearer** workflow alongside its recorder and addon:

- 🔎 Scans a selected drive progressively and groups large files into understandable collections, with safe-root exclusions and no double-counting.
- 📊 Keeps the largest 30 candidate collections current as the scan continues, while preserving your selections as later, larger results arrive.
- 🟢 Makes that ongoing work obvious: a prominent banner directly above the results now says **“SEARCH IN PROGRESS — results are still populating”** and includes the moving activity bar. The banner disappears when the scan finishes, stops, or is cancelled.
- 📁 Lets you inspect collections, select individual large files or whole folders, and open their original locations before moving anything.
- 🛡️ Adds verified, interruption-aware moves: temporary copy, flush, SHA-256 verification, collision-safe final rename, then source deletion only after success. Interrupted moves can be resumed from their restoration manifest.
- 🧪 Extends the automated suite with progressive-scan ordering, selection stability, unsafe-root protection, and move-safety coverage.

The Windows application package is rebuilt from the included `Source` folder. Live WoW Forever addon loading and real gameplay-trigger acceptance still need in-game verification. 🏴‍☠️

## 📝 Patch notes — 2026-10-25

The rolling Windows package now strengthens interrupted Disk Space Clearer moves:

- 🧾 Records durable per-file move events so a restart can distinguish a verified copy from a still-pending source.
- 🔁 Replays and trims incomplete event tails after a power loss, preserving safe resume behavior without duplicating verified files.
- 🧭 Adds the `--resume-space` recovery entry point and keeps the in-app “Resume interrupted move…” flow available.
- 🧪 The current space-recovery suite passes **41 tests**, and the full packaged harness passes **71 checks**, including native recording, clip export, and crash recovery. Live WoW Forever gameplay and addon-trigger acceptance still need in-game verification.
