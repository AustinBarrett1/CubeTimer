# CubeTimer

CubeTimer is a Rubik's Cube timer application built using Blazor and .NET MAUI. This project is designed to help Rubik's Cube enthusiasts track their solving times with additional features planned for future releases.

## Features
- **Timer Functionality**: Start, stop, and reset the timer for Rubik's Cube solves.
- **User Interface**: Responsive and user-friendly interface built with Blazor.
- **Cross-Platform**: Works across desktop and mobile devices using .NET MAUI.

## Getting Started

### Prerequisites
To run the CubeTimer project, you need the following:
- [.NET 8 SDK](https://dotnet.microsoft.com/download)
- Visual Studio 2022 or higher (with MAUI workload installed)
- Git

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/AustinBarrett1/CubeTimer.git
   cd CubeTimer
   ```

2. Open the solution file `CubeTimer.sln` in Visual Studio.

3. Restore NuGet packages:
   ```bash
   dotnet restore
   ```

4. Run the project:
   - For desktop: Click **Start** in Visual Studio.
   - For command line: Run `dotnet run` in the project directory.

### File Structure
- `wwwroot/` - Contains static assets (CSS, JavaScript, etc.).
- `Components/` - Blazor components used in the application.
- `Pages/` - Application pages (e.g., home, timer).
- `Shared/` - Shared layout and components.
- `App.razor` - Root component for the Blazor application.
- `Program.cs` - Application entry point.

## Contributing
Contributions are welcome! To contribute:
1. Fork the repository.
2. Create a new branch for your feature or bug fix.
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your fork.
   ```bash
   git commit -m "Add feature-name"
   git push origin feature-name
   ```
4. Create a pull request.

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact
For questions or feedback, please contact Austin Barrett at [abarrett3535@gmail.com](mailto:abarrett3535@gmail.com).
