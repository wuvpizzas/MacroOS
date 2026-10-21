
<img width="256" height="256" alt="download" src="https://github.com/user-attachments/assets/9694e392-34fb-4abd-94c4-9fd42908d249" />


# GitHub release copy — MacroOS v0.2.0

## Repository description

Windows macro recorder for mouse and keyboard tasks, with editable workflows, global hotkeys, and local data storage.

## Suggested topics

`windows` `macro-recorder` `desktop-automation` `dotnet` `wpf` `csharp` `hotkeys` `productivity`

## Release title

MacroOS v0.2.0 — Windows preview

## Release description

MacroOS is a Windows desktop app for recording mouse and keyboard actions and turning them into repeatable macros. Record a task, review and edit the steps, then replay it with a hotkey. For longer tasks, build a workflow from clicks, keystrokes, text, waits, repeat groups, and application launches.

This preview also includes a searchable macro library, gaming profiles, optional text shortcuts, scheduled runs, and seven themes. Settings and recordings are stored on your PC; the app does not send telemetry.

### Download and run

Download `MacroOS-v0.2.0-win-x64.zip`, extract the folder, and open `MacroOS.exe`. The package includes the .NET runtime and is for Windows 10 or 11, 64-bit. Keep the executable and README together.

### Before you use it

This is an early preview. The core automation and storage code has automated test coverage, but the Windows interface and input hooks still need a full manual verification pass. See `docs/manual-verification.md` in the source repository and report any issues with steps to reproduce.

Macro recordings can contain key codes. The optional text expander watches recent keystrokes in memory while enabled, so turn it off before typing passwords or other secrets. MacroOS cannot send simulated input to elevated applications or secure desktops.

**Platform:** Windows 10 or 11, x64  
**Package:** self-contained; no separate .NET installation required  
**License:** MIT Licensed
