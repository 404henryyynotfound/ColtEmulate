# ColtEmulate

A browser-based cross-platform OS and binary emulation workspace **built for Muir Middle School (HVS)** by **Henry Green**. Part of the **ColtApps** suite, **ColtEmulate** lets you inspect and emulate `.exe`, `.dmg`, `.iso`, `.apk`, `.deb`, and `.rom` files across separate virtualized OS environments directly in your web browser.

---

## Quick Access

### For HVS Students (No Download Required)
- **ColtEmulate Portal:** [sites.google.com/hvs.org/ColtEmulate](https://sites.google.com/hvs.org/ColtEmulate)

*(Must be signed into your HVS Google account to access the Google Sites portal.)*

### Download & Run Locally (Downloads Folder)
1. Click the **Code** button on this repository and select **Download ZIP** (or download `coltemulate.html` directly).
2. Open your computer's **Downloads** folder and extract the ZIP file if needed.
3. Double-click `coltemulate.html` to launch ColtEmulate directly in any modern web browser—no installation or admin privileges required.

---

## Features

- **Universal Binary Dropzone & Magic-Byte Inspector:** Drag and drop any `.exe`, `.dmg`, `.iso`, `.apk`, `.deb`, or `.rom` file from your computer (or use built-in sample payloads like `MuirCalc_Setup.exe`, `ColtStudio.dmg`, `ubuntu-24.04.iso`, and `RetroSnake.rom`) to inspect real binary headers (`MZ`, `UDIF koly`, `ELF`, `ISO-9660`) and auto-select the matching OS profile.
- **4 Multi-OS Virtual Machine Profiles:**
  - **ColtWin VM:** Windows 11 / Win32 compatibility layer for `.exe` and `.msi` files.
  - **ColtMac VM:** macOS Sequoia / ARM64 virtual environment for `.dmg` disk images and `.app` bundles.
  - **ColtLinux VM:** Ubuntu 24.04 LTS container environment for `.iso`, `.deb`, and `.sh` packages.
  - **ColtRetro VM:** FreeDOS / 6502 legacy hardware emulator with optional CRT scanline mode for `.rom` and `.com` files.
- **Interactive Guest Desktops & Hardware Controls:** Adjust virtual CPU cores (`1–8 vCPU`), RAM allocation (`2–16 GB`), and GPU acceleration, and run interactive installers or retro games right inside the simulated OS viewport.
- **Hypervisor Serial Console (`/dev/ttyS0`):** Toggleable bottom drawer with live boot/syscall logs and an interactive guest shell (`ls`, `uname -a`, `mount`, `run`, `clear`, `help`).

---

## Related Projects (ColtApps)

- **ColtBrowser Suite (Standard, LITE & DEV):** Privacy-focused web browser simulators powered by DuckDuckGo, also built for Muir Middle School.

---

## License & Branding

Copyright © 2026 Henry Green.

This project is licensed under the **Apache License 2.0** — see the [LICENSE](LICENSE) file for details.

**Trademark & Branding Notice:** The Apache License 2.0 does **not** grant permission to use the **ColtEmulate**, **ColtApps**, or **ColtBrowser** names, logos, or branding. If you fork or modify this project, please rebrand your version under a different name.
