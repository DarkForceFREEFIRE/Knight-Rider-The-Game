# Knight Rider: The Game — Fixes & Enhancements

*Additional fixes for **Knight Rider: The Game (2002)** by Davilex*

<p align="center">
  <img width="800" alt="Knight Rider gameplay frame" src="https://github.com/user-attachments/assets/ca498385-d95b-49aa-a584-ac5a7c78c49b" />
</p>

> **⚠️ Common issues on Windows 10/11**  
> This repository addresses **FPS drops, fullscreen problems, and lag** in *Knight Rider: The Game*.

---

## 🖥️ Fix Fullscreen Errors & Modern Hardware Lag

To resolve fullscreen glitches and performance lags on modern systems, you need **dgVoodoo2** — a wrapper that translates old DirectX calls to Direct3D 11/12.

1. Download the latest version from the official repository:  
   👉 [**dgVoodoo2 Releases**](https://github.com/dege-diosg/dgVoodoo2/releases)

2. Extract the archive and copy the following files into the **game’s root folder** (where `KnightRider.exe` is located):
   - `dgVoodooCpl.exe`
   - From `MS/x86` folder: all the `.dll` files

3. Run `dgVoodooCpl.exe` and configure the following settings

  - In the DirectX tab
   <img width="403" height="497" alt="image" src="https://github.com/user-attachments/assets/84ca4a9f-7940-4e51-8b66-62e9088e8437" />


---

## ⚡ Unlock the 25 FPS Lock

The original game is capped at **25 FPS**. Remove this limitation with a patched executable.

Download the FPS increaser from the **[Releases Page](https://github.com/DarkForceFREEFIRE/Knight-Rider-The-Game/releases/tag/FPS)**

### Instructions:
- Choose the appropriate version for your game copy.
- Replace the original `KnightRider.exe` with the patched one.
- **Remember to backup the original executable first!**

---

## ✅ Recommended Setup Summary

| Issue | Solution |
|-------|----------|
| Fullscreen errors / lag | dgVoodoo2 (DirectX wrapper) |
| 25 FPS lock | Patched executable from Releases |

After applying both fixes, launch the game and enjoy smooth, fullscreen gameplay at high frame rates on Windows 10/11.

---

*For troubleshooting, refer to the discussion section or open an issue on GitHub.*
