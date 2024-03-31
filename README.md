# ContosoPizza API

## Introduction

The ContosoPizza API is a demonstration project showcasing a simple, in-memory RESTful API for managing pizza orders. Built with ASP.NET Core, this API supports basic CRUD operations and provides a solid foundation for understanding how web APIs work in .NET environments.

## Getting Started

### Prerequisites

Before you start, ensure you have the following installed:

-   .NET 6 SDK or later
-   A preferred code editor (Visual Studio, VS Code, etc.)
-   Postman or a similar tool for testing API endpoints

### Installation

To get the project running on your machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/realYushi/ContosoPizza-API.git
    ```
2. Navigate to the project directory:
    ```bash
    cd ContosoPizza
    ```
3. Restore dependencies:
    ```bash
    dotnet restore
    ```
4. Start the application:
    ```bash
    dotnet run
    ```

## Configuration

The `launchSettings.json` file in the project defines how the application should be launched, especially in development environments. Here's a quick overview of its sections:

### `iisSettings`

Configures settings for running the application with IIS Express, including authentication modes and application URLs.

### `profiles`

Defines various launch profiles for the application:

-   **https**: For launching the application with HTTPS support.
-   **http**: For launching the application using HTTP.
-   **IIS Express**: For running the application through IIS Express with predefined environment variables and launch URLs.

Each profile includes settings for launching the browser, specifying the launch URL, defining application URLs, and setting environment variables.

### Running the Application

You can specify the launch profile directly when running the application using the .NET CLI:

```bash
dotnet run --launch-profile http
```

Or, if you are using Visual Studio, you can select the launch profile from the debug menu.

## Contributing

Your contributions are welcome! Feel free to fork the repository, make changes, and submit pull requests. If you have any suggestions or encounter issues, please open an issue in the repository.


