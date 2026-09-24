# Nwnrv

VB6 Neverwinter Nights resource viewer shell (`NWNRV.exe`, form caption "NWN Resource Viewer"). UI exposes an "NWN Directory" text box defaulting to `C:\NeverwinterNights\NWN`; module `modMain` provides `MakeLongFromStringBytes` to decode little-endian binary byte strings into Long values (hex rebuild) for reading NWN binary resource headers. Form event handlers beyond the directory field are not yet wired in this tree.

**Source last updated:** 2026-08-27 · **Language:** VB6 · **Target:** VB6 Win32 · **Output:** WinForms exe

_Note: original OneDrive LastWriteTime values were wiped to 2026-08-27 by a zip transfer; date above uses best available evidence (headers/copyright where helpful)._

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `NWNRV` (`Nwnrv.vbp`) | VB6 | WinForms exe | NWN resource viewer UI + binary byte-to-Long helper |

## How to open

Open the `.vbp` in Visual Basic 6.0 IDE:
- `Nwnrv.vbp`

## Requirements

- Visual Basic 6.0 IDE
- Local Neverwinter Nights install path (default `C:\NeverwinterNights\NWN`)

## Attribution and provenance

Working copy from my Historical Dev folder `VB/Old/Nwnrv`.
Targets Bioware Neverwinter Nights game resources.

## License

MIT (c) 2026 VaderConsulting for Dave Robinson's code. See `LICENSE`.
