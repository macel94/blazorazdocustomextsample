# Blazor Fluent UI WebAssembly Sample

This repository hosts a Blazor WebAssembly application scaffolded from the latest **Fluent UI for Blazor** templates. The project demonstrates the default Fluent UI navigation layout, counter sample, and weather data grid provided by the template.

## Getting started

1. Ensure you have the [.NET SDK 9.0.305](https://dotnet.microsoft.com/download/dotnet/9.0) or later installed.
2. Restore dependencies:
   ```bash
   dotnet restore BlazorFluentWasmApp.sln
   ```
3. Optionally run the automated checks locally:
   ```bash
   dotnet build BlazorFluentWasmApp.sln
   dotnet test BlazorFluentWasmApp.sln
   ```
4. Run the WebAssembly app locally:
   ```bash
   dotnet run --project BlazorFluentWasmApp
   ```
5. Navigate to the displayed `https://localhost` address to interact with the Fluent UI sample pages.

The `global.json` at the repository root pins the SDK version to ensure compatibility with the Fluent UI WebAssembly template.

## Development container

The `.devcontainer` folder contains a ready-to-use [Dev Container](https://containers.dev/) configuration based on the official .NET 9 image. Opening the repository in a compatible tool (such as VS Code with the Dev Containers extension or GitHub Codespaces) installs the required SDK and restores dependencies automatically.

## Continuous integration

Every pull request triggers the `CI` GitHub Actions workflow defined in `.github/workflows/ci.yml`. The workflow restores dependencies, builds the solution, and executes the test suite when test projects are present to guard against regressions.
