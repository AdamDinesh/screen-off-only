# screen-off-only

Turn off your monitor instantly without sleeping or shutting down your PC - using NirCmd.

# NirCmd – Turn Off Monitor with a Shortcut/Hotkey

A quick guide to turn off your Windows monitor instantly using a free tool called **NirCmd**, accessible via a desktop shortcut, taskbar icon, or hotkey.

---

## What is NirCmd?

**NirCmd** is a small, free command-line utility by NirSoft that can control Windows system features (monitor, volume, screensaver, and more) with a single command — no installation needed.

---

## Why use it?

Windows has no built-in way to turn off the monitor on demand. NirCmd's `monitor off` command solves this in one line, which we can wrap into a shortcut for easy access.

**Handy for:**
- Stepping away during a call without staring at the screen
- Taking a real break (not just idling with the screen on)
- Listening to music without needing the display on
- Resting your eyes during long work sessions
- Stepping back from a tough debugging session — sometimes a short break helps the answer click

---

## Download

🔗 **https://www.nirsoft.net/utils/nircmd.html**

Download the ZIP for your system:
- `nircmd.zip` — 32-bit
- `nircmd-x64.zip` — 64-bit (most PCs)

> ⚠️ Some antivirus tools flag NirCmd as a false positive — this is a known, harmless issue. Please download only from the official nirsoft.net site.

---

## Setup Steps

### 1. Extract NirCmd
Extract the ZIP to a permanent folder, e.g. `C:\Tools\NirCmd\`.

### 2. Create a Shortcut
1. Right-click Desktop → **New → Shortcut**.
2. Enter:
   ```
   "C:\Tools\NirCmd\nircmd.exe" monitor off
   ```
3. Name it `Turn Off Monitor` → **Finish**.

### 3. (Optional) Assign a Hotkey
1. Right-click the shortcut → **Properties**.
2. Click **Shortcut key** → press a combo (e.g. `Ctrl + Alt + M`) → **Apply/OK**.

### 4. Pin to Taskbar (for one-click access)
1. Right-click the shortcut → **Show more options → Pin to Start** (adds it to the Start Menu).
2. Open **Start Menu**, find the shortcut, right-click it → **Pin to taskbar**.

> 💡 On some Windows 11 versions, Windows blocks pinning shortcuts with arguments directly to the taskbar. If that happens, pinning via the Start Menu (above) usually still works.

### 5. Test It
Click the shortcut/taskbar icon or use your hotkey — monitor turns off immediately. Move the mouse or press a key to wake it.

---

## FAQ: Does this Sleep or Shutdown my PC?

**No.** `monitor off` only turns off the **display**, like pressing the power button on your monitor. Your PC keeps running normally in the background.

| Action | What happens |
|---|---|
| **Monitor off (NirCmd)** | Only the screen goes black. Music, downloads, calls, apps — all keep running. |
| **Sleep** | PC pauses (low power), resumes where you left off. |
| **Shutdown** | PC fully powers off, all apps closed. |

Move the mouse or press any key to instantly bring the screen back — everything will be exactly as you left it.

---

## Command Reference

| Command | Effect |
|---|---|
| `nircmd.exe monitor off` | Turns off the monitor |
| `nircmd.exe monitor low` | Puts monitor in low-power state |

---

## Notes
- Works on Windows 7–11.
- No admin rights typically required.

---

## License / Credit
NirCmd is developed by **NirSoft**, free for personal and commercial use. See [license terms](https://www.nirsoft.net/utils/nircmd.html).
