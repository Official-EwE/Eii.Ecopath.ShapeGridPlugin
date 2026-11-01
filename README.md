# Eii.Ecopath.ShapeGridPlugin

Plug-in for the Ecopath with Ecosim 6 Scientific Interface. Creates displays of shapes (forcing functions, mediation functions and time series) in a gridded format

## Package

- **Package ID:** `Eii.Ecopath.ShapeGridPlugin`
- **License:** EUPL-1.2
- **Icon:** `EII_plain_128x128.png`

## Build

Build the solution on Windows with the .NET SDK and .NET Framework 4.8 targeting pack:

``powershell
dotnet build .\Eii.Ecopath.ShapeGridPlugin.slnx --configuration Release
``

Packages are versioned by GitVersion in CI. The `Eii.*` dependencies require access to the Ecopath International Initiative GitHub Packages feed.

## CI/CD

The `master` branch is protected and requires pull requests to merge. Pull requests must pass the build check. Merges to `master` publish the NuGet package.