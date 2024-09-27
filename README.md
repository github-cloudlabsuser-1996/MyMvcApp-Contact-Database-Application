# MyMvcApp-Contact-Databse-Application

## Overview

MyMvcApp-Contact-Databse-Application is an ASP.NET Core MVC application designed to manage contact information. The application provides functionalities to create, read, update, and delete user contacts.

## Project Structure

The project is organized into the following directories and files:

### Directories and Files

- **.github/workflows/**: Contains GitHub Actions workflows for CI/CD.
- **appsettings.Development.json**: Configuration settings for the development environment.
- **appsettings.json**: General configuration settings for the application.
- **bin/**: Output directory for compiled binaries.
- **Controllers/**: Contains the MVC controllers.
  - **UserController.cs**: Manages user-related actions.
- **deploy.json**: Deployment configuration file.
- **deploy.parameters.json**: Parameters for deployment.
- **Models/**: Contains the data models.
  - **ErrorViewModel.cs**: Model for error views.
  - **User.cs**: Model representing a user.
- **MyMvcApp.csproj**: Project file for the application.
- **MyMvcApp.sln**: Solution file for the application.
- **obj/**: Directory for temporary object files.
- **Program.cs**: Entry point for the application.
- **Properties/**: Contains project properties.
- **README.md**: This file.
- **Views/**: Contains the MVC views.
- **wwwroot/**: Static files for the application.

### Tests

- **MyMvcApp.Tests/**: Contains unit tests for the application.
  - **UserControllerTests.cs**: Unit tests for the `UserController`.

## Getting Started

### Prerequisites

- [.NET Core SDK](https://dotnet.microsoft.com/download) installed on your machine.

### Building the Project

To build the project, navigate to the project directory and run:

```sh
dotnet build
