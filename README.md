# NodaTimeDemo

Este es un proyecto de consola en .NET que utiliza:

- Entity Framework Core
- PostgreSQL
- NodaTime para manejo de fechas/horas precisas

## ¿Qué hace?

Guarda un evento con nombre y fecha/hora actual (en formato `Instant`) usando NodaTime.

## Tecnologías

- .NET 9
- EF Core
- PostgreSQL
- NodaTime
- Npgsql.EntityFrameworkCore.PostgreSQL.NodaTime

## Comandos útiles

```bash
dotnet ef migrations add InitialCreate
dotnet ef database update
dotnet run
