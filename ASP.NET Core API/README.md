# How to bind MySql database to a Pivot Table 

A quick start project for connecting a MySql to a Syncfusion Pivot Table. This repository includes a Web API Controller ([MyWebService](../MyWebService/)) for retrieving data from a Mysql database, as well as a quick start sample in the Blazor platform that displays the retrieved data in a Syncfusion Pivot Table.

## Project prerequisites

Before beginning work on the server and client projects, ensure the following software to be installed in the machine.

* [Visual Studio 2022](https://visualstudio.microsoft.com/downloads/)
* [.NET Core SDK 6.0](https://dotnet.microsoft.com/en-us/download/dotnet/6.0) or later installed on your machine


## How to run this application?

To run this application, clone the [how-to-bind-MySQL-database-to-pivot-table](https://github.com/SyncfusionExamples/how-to-bind-MongoDB-database-to-pivot-table.git) repository.

### Using the Web API service to connect MySql to a Pivot Table

* To connect a MySql to a Pivot Table using the Web API Controller (aka, MyWebService), open the **MyWebService** project in Visual Studio 2022. Simply build and run your project in IIS Express, and it will host and display the URL `https://localhost:44346`.

* Now open the **MyBlazorServerApp** project in Visual Studio 2022. Initialize the Pivot Table, map the hosted URL, create a pivot report, and finally, run your project.