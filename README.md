# AutomationZ Config Diff

**AutomationZ Config Diff** is a lightweight **snapshot + compare (diff)** tool for server admins and modders.
It helps you quickly answer the question:

> **“What changed between version A and version B?”**

It’s perfect for debugging **broken loot**, **wrong settings**, **DayZ updates**, **wipes**, or accidental edits.

✅ Works on **Windows / Linux / macOS**  
✅ **No DayZ mod** required  
✅ Creates clean **Markdown diff reports** you can share  
✅ Beginner-friendly workflow

**Created by Danny van den Brande**

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
