# Servchk

VB6 server-check batch builder (`ServerCheck.exe`): loads a server list via ADO, picks targets and task lists, and creates `.bat` jobs (for example `dir *.[type]`, `diruse /m /*`) for selected hosts.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `ServerCheck` (`ServerCheck.vbp`) | VB6 | WinForms exe | Build per-host check batch files from ADO server lists |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `ServerCheck.vbp`

## Requirements

- Visual Basic 6.0 IDE
- ADO provider for the server-list data source used by the form

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Servchk`.

## License

MIT © 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
