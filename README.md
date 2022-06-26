# ApuriV3

> Third helper project using Blazor & .NET MAUI

## Build and run

### Windows

- Use Visual Studio
- Set the main project:
    - If you want to run MAUI project, set **MauiApuriV3** as the main project or 
    - If you want to run Blazor WebAssembly project, set **WasmApuriV3** as the main project

## macOS

- Go to the project directory that you want to use for running (e.g. with `cd` when using Terminal)
- Use a command given below depending on the project:

### MauiApuriV3

```
cd MauiApuriV3
dotnet build -t:Run -f net6.0-maccatalyst
```

### WasmApuriV3

```
cd WasmApuriV3
dotnet watch
```

(Watch includes hot-reloading feature.)