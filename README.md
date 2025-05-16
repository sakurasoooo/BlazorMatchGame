# BlazorMatchGame

This is a simple matching game built using Blazor WebAssembly.

## Getting Started

This project is a Blazor WebAssembly application. To get started, you will need the .NET SDK installed on your system.

### Prerequisites

  * [.NET SDK](https://dotnet.microsoft.com/download) (The version should be compatible with the project, typically found in a .csproj file, which is not directly provided but is standard for .NET projects)

### Running the Application

1.  Clone or download this repository.

2.  Navigate to the `BlazorMatchGame-Draft/BlazorMatchGame` directory in your terminal.

3.  Run the application using the command:

    ```bash
    dotnet run
    ```

4.  Once the application is built and running, you can access it in your web browser. The application is configured to run on the following URLs by default (as specified in `Properties/launchSettings.json`):

      * `https://localhost:5001`
      * `http://localhost:5000`

    You can also launch the project using IIS Express, which is configured to use `http://localhost:30051` and `https://localhost:44382`.

## Technologies Used

  * **Blazor WebAssembly:** The core framework for building the interactive client-side web UI with .NET.
  * **.NET:** The underlying platform.
  * **C\#:** The primary programming language used.
  * **HTML:** For structuring the web pages.
  * **CSS:** For styling the application.
      * **Bootstrap:** A popular CSS framework used for styling and layout (see `BlazorMatchGame/wwwroot/css/bootstrap/bootstrap.min.css`).
      * **Open Iconic:** An open-source icon set used within the application (see `BlazorMatchGame/wwwroot/css/open-iconic/README.md`).
  * **JSON:** Used for configuration (`launchSettings.json`) and potentially for sample data (`weather.json`, though its direct use in the game is not evident from the provided files and might be a remnant from a default template).

## Project Structure

A brief overview of the key directories:

  * `BlazorMatchGame/`: Contains the main source code for the Blazor application.
      * `Pages/`: (Typically) Contains the routable Blazor components/pages of the application.
      * `Shared/`: Contains shared Blazor components like the navigation menu (`NavMenu.razor`) and main layout (`MainLayout.razor`).
      * `wwwroot/`: The web root folder containing static assets:
          * `css/`: Contains stylesheets, including custom application styles (`app.css`) and libraries like Bootstrap and Open Iconic.
          * `sample-data/`: Contains sample data files like `weather.json`.
          * `index.html`: The main HTML page that hosts the Blazor application.
      * `Properties/`: Contains project property files, such as `launchSettings.json` which defines profiles for launching the application.
      * `Program.cs`: The main entry point for the Blazor WebAssembly application.

## About the Game

The specifics of the "Match Game" are not detailed in the provided file structure. It is a client-side Blazor WebAssembly application.
