# ws2026-semifinals-base-repo-312
## ASP.NET
### Data scaffold

`dotnet ef dbcontext scaffold "Server=.\sqlexpress;Database=Cars;Trusted_Connection=True;" 
EntityFramework.MicrosoftSqlServer --outputDir Models`

### EF CORE
`dotnet add package MySql.EntityFrameworkCore --version 8.0.8`

`dotnet tool install --global dotnet-ef`

`dotnet add package Microsoft.EntityFrameworkCore.Design`

`dotnet ef migrations add InitialCreate`

`dotnet ef database update`