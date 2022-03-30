# EF6-Code-First-Demo
Entity Framework 6 Code-First Demo Project

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

