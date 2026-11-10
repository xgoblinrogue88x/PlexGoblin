# Plex Goblin — Windows portable downloads

[Download Plex Goblin 3.4.1 Windows Portable](https://github.com/xgoblinrogue88x/PlexGoblin/raw/refs/heads/main/downloads/PlexGoblin-3.4.1-Windows-Portable.zip)

Extract the whole ZIP into a writable folder. Double-click **Launch Plex Goblin.vbs** for a console-free launch, or use **Start Plex Goblin.cmd** if Windows Script Host is disabled. No installer, Python or admin rights required. Windows PowerShell 5.1/.NET Framework are built-in Windows prerequisites; local Plex and Tautulli are separate prerequisites.

Version 3.4.1 adds a third tab, **Rules for the Revolution**, with all 16 supplied rules in gold. Text wraps and scrolls, and the tab headers wrap on narrow windows.

This preview matches Groove Goblin's blue-black/slate surfaces, green headings and purple actions. Tabs, notifications and tray menus are painted dark. Native dark scrollbars/title bars are requested on supported Windows builds. Keep all supplied files together, including GoblinTheme.ps1.

All active settings, encrypted keys and logs stay in Data beside the application. Optional desktop/startup shortcuts reference that folder. Exit fully before moving it, recreate optional shortcuts after a move, and re-enter encrypted credentials on a different Windows account or PC. Existing legacy data is migrated by copy only, without overwriting.

Includes tools/Test-WindowsUi.ps1 (offline UI checks, dummy data, bitmap captures; no playback/network) and tools/Build-WindowsPortable.ps1 (clean allowlist packaging, never installed Data). The full editable source is included in the ZIP.

Validation: PowerShell parsing; C# compilation against Windows Desktop references; source comparison of playback/security functions and handlers apart from presentation; license/privacy heuristics; ZIP manifest, CRC, and extracted-byte checks. Windows 5.1 GUI, 125%/150% DPI, and S25 Ultra visual testing remain pending on this Linux build host.

SHA-256: `0bd0677989346a660a652ea45fd44f6b3df4703c803feadf558e39bfc8e7139a`

[Previous 3.3.0 compact layout preview](https://github.com/xgoblinrogue88x/PlexGoblin/raw/refs/heads/main/downloads/PlexGoblin-3.3.0-Compact-Preview.zip)
