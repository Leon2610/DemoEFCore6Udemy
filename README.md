# DemoEFCore6Udemy

## What is Entity Framework Core?

- Entity Framework Core is a library which we can use to access databases.
- An ORM basically what it does is that it allows us to represent in objects the tables of a database.
- It allows us to work with databases without having to write SQL code directly.
- EF Core is multi-platform

## Versions

- Every year a new version of EF Core will be released
- EF Core 6 ⇒ November 2021
- EF Core 7 ⇒ November 2022
- LTS ⇒ Long-term support
- EF Core 6 is supported until November 2024
- EF Core 5 is supported until November 2022

## Ways to work with EF Core

### Code First

- We call this technique Code First, because we start with the code and then get the database.
- This has the advantage of allowing us to always have the application and the database in sync.
- Create the classes
- Configure the relationships and properties
- Generate the database

### Database First

- We start with a database already created and then we configure EF Core to work with it.

## When to use Entity Framework Core?

- When you are going to do a lot of CRUDs
- If you use recent versions of .NET
- If you need multi-platform and multi-database support.

## When not to use Entity Framework Core?

- If you have to use a technology where EF Core is not supported.
- If it does not support the database you want to use.
- Speed
- Mass operations.

## EF Core vs Dapper

- Dapper is what is known as a micro-ORM.
- In the case of Dapper, it allows you to easily map query results to C# objects.
- The EF Core 6 version had a 92% speed improvement over EF Core 5.
- In terms of memory, EF Core has reduced its usage by 43% for query execution.
- With the compiled models, the initialization speed of EF Core had an 85% improvement for a large application.
