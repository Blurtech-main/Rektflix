# 🎬 Rektflix

<p align="center">
  <img src="./0fd7f93c-d347-49e8-8ee1-b6b9bd1ee455.png" alt="Rektflix Logo" width="650">
</p>

**Clip the chaos. Keep the kill-log. Reclaim your disk space.** 🎮💾

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

