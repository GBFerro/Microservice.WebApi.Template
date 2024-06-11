# WebApi.Microservice.Template

## Introduction

The WebApi.Microservice.Template is a ready-to-use template for creating Web API microservices using .NET 8.0. This template provides a well-structured solution with predefined projects for different layers and concerns, helping you to start quickly with a solid foundation for your microservice.

## Project Structure

The template creates the following project structure:

### Project Descriptions

- **Api**: The entry point for the Web API project.
- **Domain**: Contains domain entities and business logic.
- **CrossCutting**:
  - **Configuration**: Shared configuration settings.
  - **Exceptions**: Custom exception handling logic.
- **Infrastructure**:
  - **Data**: Data access layer implementation.
  - **Data.Query**: Specific data query implementations.
  - **Service**: Service layer implementation.
- **Tests**: Unit tests for the application.

## Getting Started

### Usage

1. **Clone the repository:**
   ```sh
   git clone https://github.com/GBFerro/WebApi.Microservice.Template.git

2. **Install nuget:**
   ```sh
   Go to the root folder (Ex: cd C:/repos/WebApi.Microservice.Template)
   dotnet new install .

### Prerequisites

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) or
- [.NET 7.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) or
- [.NET 6.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0) or
- [.NET 5.0 SDK](https://dotnet.microsoft.com/download/dotnet/8.0)
- [Git](https://git-scm.com/)

##Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

##Contact
For any questions or suggestions, please reach out to Gferro.
