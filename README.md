# TodoListAPI

Simple ASP.NET Core REST API for managing a Todo List.

## Technologies

- .NET 8 SDK
- ASP.NET Core
- Entity Framework Core
- SQLite
- Swagger

## Installation

1. Install .NET 8 SDK: https://dotnet.microsoft.com/en-us/download/dotnet/8.0

2. Clone the repository and restore dependencies:

```bash
git clone github.com/damianlebiedz/TodoListAPI.git
cd TodoListAPI
dotnet restore
```
3. Set up the database and run the application:
```
dotnet tool install --global dotnet-ef
dotnet ef migrations add InitialCreate
dotnet ef database update
dotnet run
```
4. Open the browser at the port shown in the terminal (default: http://localhost:5001/swagger) and test the API using Swagger UI.

## Contact

Damian Lebiedź | https://damianlebiedz.github.io/contact.html
