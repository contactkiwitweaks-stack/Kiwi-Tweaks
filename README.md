<div align="center">

# 🥝 Kiwi's Tweaking Utility 2.0
### *Transparent Windows Latency, Performance & Gaming Optimization*

<p align="center">
  <a href="https://github.com/contactkiwitweaks-stack/Kiwi-Tweaks/releases"><img src="https://img.shields.io/badge/Release-2.0%20Official-00d2d3?style=for-the-badge&logo=github" alt="Release"></a>
  <a href="https://discord.gg/kiwitweaks"><img src="https://img.shields.io/badge/Discord-Join%20Community-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord"></a>
  <a href="https://microsoft.com/windows"><img src="https://img.shields.io/badge/Windows-10%20%7C%2011-0078d4?style=for-the-badge&logo=windows&logoColor=white" alt="Windows"></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-Custom%20NC--ND-6c5ce7?style=for-the-badge" alt="License"></a>
  <a href="https://github.com/contactkiwitweaks-stack/Kiwi-Tweaks/stargazers"><img src="https://img.shields.io/github/stars/contactkiwitweaks-stack/Kiwi-Tweaks?style=for-the-badge&color=ff9f43&logo=star&logoColor=white" alt="Stars"></a>
</p>

<p align="center">
  <a href="https://raw.githubusercontent.com/contactkiwitweaks-stack/Kiwi-Tweaks/main/Kiwi%20Tweaking%20Utility%202.0.bat"><img src="https://img.shields.io/badge/Download-Utility%202.0%20(.bat)-2ecc71?style=for-the-badge&logo=windows-terminal&logoColor=white" alt="Download"></a>
  <a href="https://kiwitweaks.vercel.app/"><img src="https://img.shields.io/badge/Website-kiwitweaks.vercel.app-00cec9?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Website"></a>
  <a href="https://github.com/contactkiwitweaks-stack/Kiwi-Tweaks/issues"><img src="https://img.shields.io/badge/Support-Report%20Issue-ff6b6b?style=for-the-badge&logo=github" alt="Report Issue"></a>
</p>

<p align="center">
  A lightweight, transparent, and batch-native optimization engine designed to lower DPC latency, eliminate frame drops, and optimize CPU/GPU/network scheduling for competitive PC gaming.
</p>

<!-- 
GitHub SEO & Discovery Metadata:
windows-optimization, pc-tweaks, fps-boost, latency-reduction, input-lag-fix, gaming-tweaks,
fortnite-fps-boost, valorant-optimization, cs2-tweaks, apex-legends-fps, warzone-tweaks, roblox-fps,
regedit-tweaks, bcdedit-optimization, cpu-core-unparking, gpu-msi-mode, tcp-optimizer, network-latency,
windows-10-debloat, windows-11-debloat, timer-resolution, mmcss-priority, dscp-qos, competitive-pc-gaming
-->

---

</div>

## ⚡ Quick Start

### One-Line Auto Download & Launch
Open **PowerShell (Run as Administrator)** and paste the command below:

```powershell
$s = (New-Object Net.WebClient).DownloadString('https://raw.githubusercontent.com/contactkiwitweaks-stack/Kiwi-Tweaks/main/Kiwi%20Tweaking%20Utility%202.0.bat'); [IO.File]::WriteAllText("$env:TEMP\Kiwi.bat", ($s -replace "`r?`n", "`r`n"), (New-Object Text.UTF8Encoding($false))); (New-Object -ComObject 'Shell.Application').ShellExecute('cmd.exe', "/k `"`"$env:TEMP\Kiwi.bat`"`"", '', 'runas', 1)
```

### Manual Installation
1. Download [Kiwi Tweaking Utility 2.0.bat](Kiwi%20Tweaking%20Utility%202.0.bat).
2. Right-click the file and select **Run as Administrator**.
3. Create a System Restore Point when prompted on initial launch.

---

## Key Highlights

- **Universal Backup & Revert Engine**: Snapshot current registry and network settings or restore Windows factory defaults with one click ([0] Backup & Restore).
- **Hardware Architecture Detection**: Automatic CPU core topology detection (Intel P/E cores, AMD Ryzen 3D V-Cache) and GPU vendor identification.
- **Esports Game Priority & QoS**: Dedicated high process priority and DSCP 46 packet routing for top competitive games (Fortnite, Valorant, CS2, Apex, Warzone, R6 Siege, Overwatch 2, Rust, Roblox, League of Legends, GTA V).
- **Broadband TCP Modernization**: Enabled Selective ACKs (SACK), configured CUBIC congestion provider, and removed legacy dial-up bandwidth limits.
- **100% Transparent Source Code**: Delivered as plain human-readable .bat code without any compiled binary executables.

---

## 📋 Changelog

### Version 2.0 (Official Release) - 2026
- **Added Universal Backup & 1-Click Revert System**: Real-time snapshot generation for TCP, Multimedia, GameDVR, and Mouse registry hives.
- **Added Hardware-Adaptive Detection**: Queries CPU manufacturer/model and primary GPU on startup to display system specs in the main header.
- **Added 6 New Competitive Game Profiles**: Integrated Call of Duty (Warzone/MW3), Rainbow Six Siege, Overwatch 2, Rust, Roblox (Bloxstrap), and League of Legends.
- **Modernized Network Stack**: Switched default TCP congestion provider to CUBIC, enabled Selective ACKs, and restored standard TCP Window Auto-Tuning.
- **Resolved All Menu Routing Flaws**: Fixed 53 duplicate redirection labels, eliminating infinite loop bugs and menu jump crashes.
- **Anti-Cheat Hardening**: Verified safe execution with Riot Vanguard, EasyAntiCheat, BattlEye, VAC, and Ricochet.
- **Codebase Optimization**: Formatted and cleaned trailing empty lines, standardized 4-space loop indentation, and verified 0 syntax errors across all 10,900+ lines.

### Version 1.5 (Legacy Release)
- Consolidated CPU power index, GPU driver tweaks, USB latency options, and basic game priority settings into a unified multi-menu batch interface.

---

## 📜 License

Distributed under the **Kiwi Tweaks Public License (Non-Commercial, No-Derivatives)**.
- Free to download, run, share, and redistribute verbatim unmodified copies.
- Commercial sale, monetization, paywalling, or unauthorized modifications and derivative rebrands are strictly prohibited.
- See [LICENSE](LICENSE) for complete legal terms.

<div align="center">
  <sub>Built with ❤️ by the Kiwi Tweaks Community.</sub>
</div>