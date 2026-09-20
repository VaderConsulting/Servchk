# Servchk

VB6 server-check batch builder (`ServerCheck.exe`): loads a server list via ADO, picks targets/task lists, and creates `.bat` jobs (e.g. `dir *.[type]`, `diruse /m /*`) for selected hosts. Open `ServerCheck.vbp` in the VB6 IDE.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ServerCheck` (`ServerCheck.vbp`) | VB6 | WinForms exe | Build remote server check `.bat` files from ADO list |
