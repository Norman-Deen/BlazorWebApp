# BlazorWebApp — .NET 8 Full-Stack Coursework

An educational Blazor solution developed during my full-stack studies at EC Utbildning. The repository contains an ASP.NET Core host and a separate Blazor WebAssembly client, rather than a standalone static frontend.

## Structure

- `BlazorWebApp/BlazorWebApp/`: server host, components, configuration, and static assets.
- `BlazorWebApp/BlazorWebApp.Client/`: WebAssembly client project.
- `BlazorWebApp.sln`: solution entry point.

## Local development

Use the .NET 8 SDK. Review application configuration and provide the required local database/service settings before running.

```bash
git clone https://github.com/Norman-Deen/BlazorWebApp.git
cd BlazorWebApp
dotnet restore BlazorWebApp.sln
dotnet run --project BlazorWebApp/BlazorWebApp/BlazorWebApp.csproj
```

Use the address printed by the host. Server-side features require an ASP.NET Core runtime; GitHub Pages alone cannot host them.

## Scope

This is coursework demonstrating C#, Razor components, and web application integration. It is retained as part of my full-stack development foundation.

[Nour Altinawi — Nourtin](https://nourtin.com/) · [Current real-time 3D work](https://github.com/Norman-Deen)
