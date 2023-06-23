# Managing dependencies in a dotnet project with the CLI
This is the first mini project of the official **Build .NET applications with C#** in the Microsoft Learn platform.

## Objective
- Add a package.
- Use it in your code, and then check if there is a newer version.
- Install that newer version.

## Used commands

    dotnet new console -f net6.0
    dotnet add package Humanizer --version 2.7.9
    dotnet run
    dotnet list package --outdated
    dotnet add package Humanizer