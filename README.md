![Aurora Project](https://repository-images.githubusercontent.com/128673011/f6ebdd80-b6da-11ea-94bb-9d141944b257)

# What is Aurora project?
It's an open source project, written in .NET Core, currently in version 3.1.

The project's goals is to show that is possible to create an architecture more simple than others and using some concepts like DDD (Design Driven Design).

## How to use:
1. Clone this project to into your machine
2. Use the default connection string or:
    2.1. Install and configure [MySql](https://dev.mysql.com/downloads/mysql/), if you want.
    2.2. Inform the connection string on Aroura.Infra.Data/Context/MySqlContext.cs, if necessary
    * Put the server name on [SERVER] tag
    * Put the port number on [PORT] tag
    * Put the user name database on [USER] tag
    * Put the password database on [PASSWORD] tag
4. Finally, build and run the application

## MySql Migrations:
1. Open your Package Manager Console
2. Change the default project to Aurora.Infra.Data
3. Run command "Add-Migration [NAME OF YOUR MIGRATION]"
4. Run command "Update-Database"

For more information about this project, sse this [article](https://medium.com/@alexalves_85598/criando-uma-api-em-net-core-baseado-na-arquitetura-ddd-2c6a409c686).

## Technologies implemented:
* ASP.NET Core 3.1 (com .NET Core 3.1)
* Entity Framework Core 2.0.2
* FluentValidation 7.5.2
* Swagger UI 5.5.0
* MySql Database Connection
* .NET Core Native DI

## Architecture:
* Layer architecture
* Domain Driven Design
* Clean Code
* Dependency Inversion Principle (S O L I **D**)
* Interface Segregation Principle (S O L **I** D)

## News:
**v1.1 --- 2020-06-24**
* Updated the project name
* Updated the project's SDK to .NET Core 3.1 version
* Added the Swagger framework to document the API
* Corrections to end-points
* Published in [Azure](http://aurora-project.azurewebsites.net/swagger/index.html)

**v1.0 --- 2018-06-09**
* Create the project in .NET Core 2.0 version
* Structured the project on layer architecture 
* Used the Service layer to business rules
* Used the FluentValidation library
* Configured the connection to MySql database
* Used EntityFramework

## Why Aurora?
The name Aurora came from the natural event called Aurora Borealis. It is a scientific event described by the interaction between the earth's magnetic layer and energized particles from the solar wind.

A curiosity about such an event is that what we see in photographs is not always the same image that is seen live.

For more information, look this [link](https://www.hipercultura.com/fenomenos-naturais/).

## We're online!
See the project in [Azure](http://aurora-project.azurewebsites.net/swagger/index.html).

## About:
The Aurora project was developed by [Alex Alves](https://www.linkedin.com/in/alexalvess/).
