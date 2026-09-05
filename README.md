# CtrlCloneTst

C# Windows Forms harness that exercises a `ControlFactory` helper for cloning WinForms controls and for copy/paste through the clipboard. Buttons on the main form clone or copy a ComboBox and a PictureBox, then paste a serialized control back onto the form so you can compare clone versus clipboard round-trip behaviour. This is an early Visual Studio .NET 2003 / .NET 1.1 proof-of-concept; a related VB.NET ControlFactory later appears in the Cables CPULL browser.

**Source last updated:** 2006-02-21  
**Language:** C#  
**Target:** .NET Framework 1.1  
**Output:** WinExe

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `CtrlCloneTst` | C# | WinForms exe | Demo host for ControlFactory clone and clipboard copy/paste |

## How to open

Open `CtrlCloneTst.sln` in Visual Studio. The checked-in project file is `CtrlCloneTst/CtrlCloneTst.csproj.example` (credentials/paths redacted); rename or copy to `CtrlCloneTst.csproj` before building if your IDE requires the un-suffixed name.

## Requirements

- Visual Studio .NET 2003
- .NET Framework 1.1

## Attribution and provenance

- Historical working copy from Dave Robinson / VaderConsulting.
- No third-party source-code attribution markers were identified in assembly metadata (blank AssemblyTitle/Company). ControlFactory-style helpers were common community samples in this era; treat this tree as Dave's local test copy unless a clearer upstream is documented.

## License

MIT. See `LICENSE`.
