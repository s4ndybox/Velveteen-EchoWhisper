# Velveteen EchoWhisper

> A PowerShell-based forensic sweeper for detecting malware persistence via YARA scans, autoruns, scheduled tasks, and WMI event consumers.

## 📌 Features

- 🧬 YARA memory scanning
- 🔁 Autorun registry inspection
- ⏰ Scheduled task analysis
- ⚙️ WMI EventFilter detection
- 🔒 Automatic quarantine of suspicious binaries
- 🧾 Timestamped log file generation

## 🧪 Requirements

- PowerShell 5.1+
- [YARA](https://github.com/VirusTotal/yara) installed at `C:\Tools\YARA\yara64.exe`
- YARA rules file at `C:\Tools\YARA\rules.yar`

## 📂 Folder Structure

```
Velveteen-EchoWhisper/
├── Velveteen-EchoWhisper.ps1
├── README.md
├── LICENSE
└── Tools/
    ├── yara64.exe
    └── rules.yar
```

## 🚀 Usage

1. Clone or download this repository.
2. Ensure `yara64.exe` and `rules.yar` are located under `Tools/` or edit the script path accordingly.
3. Run the script as administrator:

```powershell
.\Velveteen-EchoWhisper.ps1
```

4. A log file will be generated in:

```
%OneDrive%\Desktop\VelveteenReports\Velveteen-Removal-Log_yyyy-mm-dd.txt
```

## ⚠️ Disclaimer

This tool is provided for educational and defensive use only. Use at your own risk.

---

MIT Licensed © 2025 Velveteen Security Labs
