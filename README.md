# Minimal C# .NET Core 8.0 API

This is a minimal C# .NET Core 8.0 API project for a [Microsoft Learn](https://learn.microsoft.com) course.

## Prerequisites

- Run `dotnet --list-sdks` to get the list of installed .NET Core SDKs. Then check if you have `8.0.x` installed.
- VS Code

## Getting started

- Clone the repository
- Run `dotnet build` to generate the project
- Run `dotnet ef migrations add InitialCreate`
- Run `dotnet ef database update`
- Run `dotnet run`
- Go to [localhost](http://localhost:5000) to see if the app is running

## Swagger

Find the Swagger Docs at [Swagger](http://localhost:5000/swagger)
