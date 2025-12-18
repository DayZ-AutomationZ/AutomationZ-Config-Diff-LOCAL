# AutomationZ Config Diff [![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R51QD7BU)
**Build for my DayZ Server to compare backups of files / folders which i make before making changes. 
If i encounter a error i can download the current files make 2 snapshots and compare the snapshots and see the changes made in the report files.
**No DayZ mod** required can be used for any Game / server, website, whatever has folders and files!**
[![Config_Diff_Set_name.png](https://i.postimg.cc/x8Ytps1q/Config_Diff_Set_name.png)](https://postimg.cc/JD6NG5JW)
**AutomationZ Config Diff** is a lightweight **snapshot + compare (diff)** tool for server admins and modders.
It helps you quickly answer the question:

> **“What changed between version A and version B?”**

It’s perfect for debugging **broken loot**, **wrong settings**, **DayZ updates**, **wipes**, or accidental edits.

✅ Works on **Windows / Linux / macOS**  
✅ Creates clean **Markdown diff reports** you can share  
✅ Beginner-friendly workflow

---

## What this tool is for

### DayZ server admins
- Compare `cfggameplay.json`, `types.xml`, `events.xml`
- Track changes after updates, wipes, or mod edits

### Any folder comparison
- Snapshot folders before changes
- Snapshot again after
- Diff to instantly see what broke

---

## How it works

1. **init** – creates `config/settings.json`
2. **snapshot** – copies tracked files into `snapshots/`
3. **diff** – compares two snapshots and writes a Markdown report

Nothing is modified. Files are only copied and compared.

---

## Quick Start

### Windows
Run:
- `run_windows.bat`

### Linux / macOS
```bash
python3 app/main.py
```

---

## Typical workflow

1. Init
2. Edit settings.json
3. Snapshot BEFORE
4. Make changes
5. Snapshot AFTER
6. Diff and read report

---

## Hosted servers (Nitrado etc.)

Download configs via FTP → snapshot → change → download again → snapshot → diff.

---

## FAQ

**Is this a DayZ mod?**  
No.

**Does it change my server files?**  
No.

**Does it work on Linux?**  
Yes.

---

## Credits
Created by **Danny van den Brande**  
Part of **AutomationZ**
