---
title: Velveteen EchoWhisper
layout: default
---

<style>
body {
  background-color: #0d1117;
  color: #c9d1d9;
  font-family: 'Courier New', Courier, monospace;
}
a {
  color: #58a6ff;
}
pre {
  background-color: #161b22;
  padding: 10px;
  border-radius: 6px;
  overflow-x: auto;
}
</style>

# 🕵️ Velveteen EchoWhisper

A stealth-mode PowerShell sweeper to detect and disrupt malware persistence on Windows systems.

- 🧬 Memory scanning via YARA
- 🔁 Registry autorun hunting
- ⏰ Scheduled task auditing
- ⚙️ WMI event consumer tracking
- 🔒 Quarantine of live threats
- 🧾 Automatic logging

---

## 🔧 Usage

```powershell
.\Velveteen-EchoWhisper.ps1
```

- Log will be saved in: `%OneDrive%\Desktop\VelveteenReports\Velveteen-Removal-Log_yyyy-mm-dd.txt`
- Suspicious files will be copied to `C:\Forensics\Quarantine`

---

## 📦 Download

Latest release: [GitHub Releases](https://github.com/YOUR_USERNAME/Velveteen-EchoWhisper/releases)

---

## 🛡️ License

MIT — for defenders, researchers, and digital rebels.
