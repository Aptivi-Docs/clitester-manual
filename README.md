---
description: Welcome to CliTester!
icon: hand-wave
---

# Welcome

Welcome to CliTester! It's a C# library that allows you to define test fixtures to test some of the functions that are not normally done on unit test projects. This is useful to test functions that require full console access. To use this library, go to any page in the left side of the screen.

## Installation

This library is very easy to install. It's available at [NuGet](https://www.nuget.org/packages/CliTester/). Just follow these steps:

1. Open your project file (`.csproj` or `.fsproj`)
2. Place the `PackageReference` line on a property group like so:
   * `<PackageReference Include="CliTester" Version="x.x.x" />`
   * ...where `Version` is the current version of the library
3. Run a package restore using `dotnet restore`

If you follow these steps correctly, you should be able to use this library's functions.
