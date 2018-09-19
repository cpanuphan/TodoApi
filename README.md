# TodoApi

This TodoApi create using ASP.NET Core 2.1 and use Sqlite Database

## Development

Before you run the project you need to install Entity Framework pacakge and initial Database
### Install Entity Framework
Run `dotnet add package Microsoft.EntityFrameworkCore.Sqlite`
Run `dotnet add package Microsoft.EntityFrameworkCore.Design`
Run `dotnet restore`
### Initial Database
Run `dotnet ef migrations add InitialCreate`
Run `dotnet ef database update`

## Launch the app
In Visual Studio, press CTRL+F5 to launch the app. Visual Studio launches a browser and navigates to http://localhost:<port>/api/values, 
where <port> is a randomly chosen port number.
