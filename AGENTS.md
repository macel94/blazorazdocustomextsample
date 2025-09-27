# Agent Instructions

These instructions apply to the entire repository.

## Code Style
- Prefer the latest .NET SDK specified in `global.json` for builds and tooling.
- Follow C# best practices: use `var` for local type inference when the type is evident, favor expression-bodied members when concise, and keep components in PascalCase.
- Keep Razor components well-organized: group parameters at the top, markup in the middle, and code blocks (if any) at the bottom.

## Testing
- Run `dotnet build` for the `BlazorFluentWasmApp` project after making changes.
- Add additional automated tests as they are introduced in the solution.

## Documentation
- Update the README when setup steps or developer workflows change.
- Document new scripts or manual steps in repository docs.

## Pull Requests
- Summarize notable changes and list the commands executed for validation in the PR description.
