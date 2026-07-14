Prerequisites
- .NET 8 SDK
- Node.js
- Angular CLI
- SQL Server

Backend

dotnet restore
dotnet ef database update
dotnet run

Database Setup

By default, the project is configured to use **LocalDB**. If you are using a dedicated SQL server, you can override this locally:
1. Open the `appsettings.Development.json` file (or create it if it does not exist).
2. Modify the `DefaultConnection` value to point to your local server.
3. Do not push changes made to `appsettings.Development.json` to the production environment or Git.

Frontend

npm install
ng serve

Application URLs

Backend:
https://localhost:5001

Frontend:
http://localhost:4200
