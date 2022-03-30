# EF6-Code-First-Demo-of-Conversion-to-EFCore
Entity Framework 6 Code-First Demo Project Migrated to Entity Framework Core

Reinstated into .NET 4.8 Project [here](https://github.com/Amondale/ef6dbfirst)


## Modifications made to modernize

### 1. Added NuGet packages

Microsoft.EntityFrameworkCore.Design and other designers (SQLite, MYSql, etc.)

### 2. Added Connection Strings

	<connectionStrings>
		<add name="EFCore"
		  providerName="System.Data.SqlClient"
		  connectionString="Server=(localdb)\mssqllocaldb;Database=EFCore;Integrated Security=True;"/>
	</connectionStrings>

### 3. Ran migrations

`dotnet add-migration ...`
`dotnet update-database`

### 4. Built the updated demo

Received the exciting response from app:
    
    EF6CodeFirstDemo> dotnet run

    Demo completed.

Yay!

### 5. ERD from LocalDB

![dbfirst](https://user-images.githubusercontent.com/8033475/160741337-715cfa6f-818a-40b2-9154-acf3b4d2dd57.png)
