# VaderConsulting.Designer

C#.NET 4.6 WinForms MDI Designer with a left palette of Drawing, Server, Disk, Windows Service, Application, Database, Agreement. `Program.Main` runs `frmParent` (window title Designer), an MDI container with File/Edit/View/Tools/Windows/Help menus from the Visual Studio MDI parent template. The Drawing button opens empty `frmDrawing` as a maximised MDI child; the other palette buttons have tooltips but no click handlers yet. Open and Save As show file dialogs without loading or writing content; cut, copy, and paste handlers are empty.

**Source last updated:** 2015-10-05 · **Language:** C# · **Target:** .NET Framework 4.6 · **Output:** WinForms executable (`WinExe`)

## Solution structure

| Project | Language | Type | Purpose |
|---------|----------|------|---------|
| `Designer` (`Designer.csproj`) | C# | WinForms exe (`net46`) | MDI shell with palette buttons for Drawing, Server, Disk, Windows Service, Application, Database, Agreement. |

## How to open

Open `Designer.csproj` in Visual Studio 2015 or later (ToolsVersion 14.0). There is no `.sln` in this folder.

## Requirements

- Visual Studio 2015 or later, .NET Framework 4.6

## Attribution and provenance

Working copy from Dave Robinson's OneDrive Historical Dev folder `VaderConsulting.Designer`. Assembly title/product `Designer`; copyright `Copyright ©  2015`; company empty. Namespace `Designer`. Folder name on disk is `VaderConsulting.Designer`. Embedded PNG resources: `Blueprint_blue_256`, `Server2_blue_256`, `hard_disk_256`, `gear_blue_256`, `Setup_blue_256`, `database_blue_256`, `contract2_256_blue`.

## License

MIT © 2026 VaderConsulting. See `LICENSE`.
