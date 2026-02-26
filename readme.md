# backend-learning

Proyecto para aprender backend paso a paso.

## Stack
- .NET 8 (ASP.NET Core Web API)

## Instalacion de .NET SDK (Windows)
Si `dotnet --version` falla, instala el SDK 8:
- Opcion 1: https://dotnet.microsoft.com/download/dotnet/8.0
- Opcion 2 (winget): `winget install Microsoft.DotNet.SDK.8`

Luego cierra y abre la terminal, y verifica:
```bash
dotnet --version
```

## Crear API .NET
```bash
dotnet new webapi -n BackendLearning.Api
cd BackendLearning.Api
dotnet run
```

## Probar API
Abre la URL que muestra la consola en `/swagger`.
