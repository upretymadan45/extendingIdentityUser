# extendingIdentityUser

# Nuget packages required
1. dotnet tool install -g dotnet-aspnet-codegenerator
2. dotnet add package Microsoft.VisualStudio.Web.CodeGeneration.Design

# Command to generate identity related files
dotnet aspnet-codegenerator identity -dc ExtendingIdentityUser.Data.ApplicationDbContext --files "Account.Register;Account.Login"
