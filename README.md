# CRUD Operations in ADO.NET with ASP.NET Core
In this repository I have perfomred CRUD Operations (CREATE, READ, UPDATE & DELETE) on a Teachers table in the Database.

![CRUD Operations](https://raw.githubusercontent.com/yogyogi/CRUD-Operations-in-ADO.NET-with-ASP.NET-Core/master/CRUD-Operations-in-ado-net-ASPNET-Core.png)

## Compatible with ASP.NET Core MVC 2.0, 2.2, 3.1 & 5.0

This repository is made for beginners who want to learn 3 things:

1. [ASP.NET Core](https://www.yogihosting.com/category/aspnet-core/)
2. ADO.NET
3. CRUD Operations

Download this repository and open it in Visual Studio. Then create the database and teachers table in it. Finally change the connection string given inside the appsetting.json file and you are set to go:

```
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\MSSQLLocalDB;Database=School;Trusted_Connection=True;MultipleActiveResultSets=true"
  }
}
```


# How to create Teacher table

Run the following script to create the Teacher table in your database.

```
CREATE TABLE [dbo].[Teacher]
(
    [Id] INT NOT NULL IDENTITY(1,1) PRIMARY KEY,
    [Name] VARCHAR(50) NOT NULL,
    [Skills] VARCHAR(250) NOT NULL,
    [TotalStudents] INT NOT NULL,
    [Salary] MONEY NOT NULL,
    [AddedOn] DATE NOT NULL DEFAULT GETDATE()
)
```

# Wait, There is more for you

I have explained each and every area of the code in my HACKERNOON article - [ASP.NET CORE — Learn CRUD Operations in ADO.NET from Zero to Hero](https://hackernoon.com/asp-net-core-learn-crud-operations-in-ado-net-from-zero-to-hero-a0109ed2f8a4)

## Support

If you find it useful then support this Project. Thank you.

<a href="https://www.buymeacoffee.com/YogYogi" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" width="200"></a>

## Dont forget to Star this repository. Thank You !
