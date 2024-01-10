To configure this webapp contexts start with connecting the Npgsql server after conncting the server
Click on the CreateDatabase.bat from this folder to create/update the database or 
Open the NuGet Package Manager Console 
start with typing: cd DVDRental
and type: dotnet ef database update --context ApplicationDbContext
finally type dotnet ef database update --context Identitycontext
