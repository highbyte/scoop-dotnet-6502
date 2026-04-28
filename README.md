# Scoop Bucket for DotNet6502

Scoop bucket for the [DotNet6502](https://github.com/highbyte/dotnet-6502) emulator — a 6502 CPU and C64 emulator built with .NET and Avalonia.

## Available apps

| Name | Description |
| --- | --- |
| `dotnet-6502` | 6502 CPU and C64 emulator built with .NET and Avalonia (desktop GUI) |
| `dotnet-6502-headless` | Headless 6502/C64 emulator driven by CLI arguments and Lua scripts |
| `dotnet-6502-remote` | Remote control CLI client for the dotnet-6502 emulator |

## Installation

Add the bucket once:

```powershell
scoop bucket add dotnet-6502 https://github.com/highbyte/scoop-dotnet-6502
```

Then install the app(s) you want:

```powershell
scoop install dotnet-6502
scoop install dotnet-6502-headless
scoop install dotnet-6502-remote
```

## Updating

```powershell
scoop update dotnet-6502
scoop update dotnet-6502-headless
scoop update dotnet-6502-remote
```

## Uninstalling

```powershell
scoop uninstall dotnet-6502
scoop uninstall dotnet-6502-headless
scoop uninstall dotnet-6502-remote
scoop bucket rm dotnet-6502
```
