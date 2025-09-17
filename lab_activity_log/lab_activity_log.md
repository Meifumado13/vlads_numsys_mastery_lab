# Lab Activity Log — 09/16/2025

## Timeframe
Start: 00:00 UTC−4  
End: 11:09 UTC−4  

---

## Phase 1 — Gathering & Structuring Source Material
- Collected all source materials: PDFs, HTML pages, visual references, and additional notes.
- Created preliminary folder structure on Desktop for organization:

  ```bash
  mkdir vlads_numsys_mastery_lab           # main lab folder
  mkdir vlads_numsys_mastery_lab/assets    # asset files
  mkdir vlads_numsys_mastery_lab/docs      # documentation
  mkdir vlads_numsys_mastery_lab/notes     # notes + cheat sheets
  mkdir vlads_numsys_mastery_lab/scripts   # scripts / code
  mkdir vlads_numsys_mastery_lab/lab_activity_log  # lab logs
  ```
- Verified folders successfully created and visible in Finder/VS Code.
- Planned file names for consistency: lowercase letters with underscores instead of spaces or dashes.

---

## Phase 2 — Populating with Initial Assets
- Moved core reference files into `assets/`:

  ```bash
  mv ~/Desktop/ascii_bindechex_conv.html ./assets/
  mv ~/Desktop/dcc_decbinhex_chart.pdf ./assets/
  ```
- Confirmed files open correctly in browser/PDF reader.
- Corrected file names to match naming conventions (underscores, lowercase).
- Verified visibility of all files in Obsidian by toggling "Detect all file extensions."

---

## Phase 3 — Notes & Documentation Setup
- Inside `notes/`, created dedicated `.md` file for CLI commands and workflows:

  ```bash
  touch vlads_numsys_mastery_lab/notes/cli_cheats.md
  ```
- Created the Lab Activity Log file inside its folder:

  ```bash
  touch vlads_numsys_mastery_lab/lab_activity_log/lab_activity_log.md
  ```
- Opened lab vault in VSCode from main lab folder:

  ```bash
  code .
  ```
- Recognized `.obsidian` folder and JSON config files generated automatically by Obsidian.

---

## Notes & Observations
- VS Code launched from the **lab root folder**; sidebar shows expected structure:

  ```
  vlads_numsys_mastery_lab/
  ├── .obsidian/         # config + JSON files
  ├── assets/
  │     ├── ascii_bindechex_conv.html
  │     └── dcc_decbinhex_chart.pdf
  ├── docs/
  ├── notes/
  │     └── cli_cheats.md
  ├── scripts/
  └── lab_activity_log/
        └── lab_activity_log.md
  ```
- Verified assets display properly in left-hand panel.
- Folder and file names standardized with underscores instead of dashes.
- `.obsidian/` auto-generated with JSON + config files.
- Holding to proper naming conventions from "Save As" dialog prevents later renaming headaches.
- Use `mv "old name"` with quotes when spaces exist.

---

## Key Commands Used

```bash
pwd               # show current directory
ls, ls -la        # list files / list all including hidden
cd                # navigate directories
mkdir             # create directories
touch             # create empty files
mv                # move & rename files/folders
cp                # copy files/folders
rm, rmdir, rm -r  # remove files/folders
code .            # open VSCode in current directory
Ctrl + P / Cmd + P # Quick Open in VSCode
```

* CLI cheat sheet saved as `notes/cli_cheats.md` for ongoing workflow mastery.

---

## Mistakes & Learning
- Forgot the `.` when moving files from Desktop → `assets/`.
- Misspelled filenames initially; renaming using `mv` helped muscle memory.
- Not toggling "Detect all file extensions" initially in Obsidian.
- Learned to recognize `.obsidian` folder structure and JSON configs.

---

## Next Steps
- Create Hub Node (main reference node) in Obsidian for lab.
- Begin linking HTML/PDF files from `assets/` into Hub Node.
- Continue cataloging commands in CLI cheat sheet for workflow mastery.

---

## Appendix: All Commands Run

```bash
# Phase 1 — create base lab structure
mkdir vlads_numsys_mastery_lab
cd vlads_numsys_mastery_lab
mkdir assets docs notes scripts lab_activity_log

# Phase 2 — move reference files into assets
mv ~/Desktop/ascii_bindechex_conv.html ./assets/
mv ~/Desktop/dcc_decbinhex_chart.pdf ./assets/

# Phase 3 — create notes + log files
touch notes/cli_cheats.md
touch lab_activity_log/lab_activity_log.md

# Open VSCode from lab folder
code .
```
