# Lab41_ASPNET46
Re-create an ASP.NET 4.6 code base

---
## Objective
Create an ASP.NET Core 4.6 MVC website with the guidance of [tutuorial](https://docs.microsoft.com/en-us/aspnet/mvc/overview/getting-started/introduction/).

---
## Overview
MVC stands for Model View Controller and is a architectural pattern than can be used
in website implementation.  

The **Model** is made of classes that represent the data of the app.
In this app the model will retrieve movie information from a database, provides to
the view and it will update the data, which will be written to a database.

The **View** is the User Interface that displays the information to the user.

The **Controller** is made of classes that handles the browers requests.
The controllers handles and responds to user input and interaction.

This tutorial goes over a previous version of the .NET Framework.

---
## Dependencies
This application runs on .NET Core 2.1, which can be downloaded [here](https://www.microsoft.com/net/download/macos).

---
## Build
After installing the [.NET Core 2.1 SDK](https://www.microsoft.com/net/download/macos), clone this repo onto your machine. From a terminal interface, go to where this was cloned and type the following commands:

```
cd Lab41_ASPNET46
dotnet restore
dotnet run
```
---

## Screenshots
Initial index page:

![Initial Index Page]()

New landing page:

![New Landing Page]()

New movie list page design:

![Initial Index Page]()


