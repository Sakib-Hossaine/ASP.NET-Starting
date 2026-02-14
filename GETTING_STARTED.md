# Getting Started with ASP.NET Learning

This guide will help you set up your environment and start learning ASP.NET Core.

## Prerequisites

Before you begin, make sure you have:

1. **.NET SDK** - Download from [dotnet.microsoft.com](https://dotnet.microsoft.com/download)
2. **Code Editor** - Visual Studio, Visual Studio Code, or Rider
3. **Git** - For version control
4. **Basic C# knowledge** - Understanding of C# fundamentals

## Setup Steps

### 1. Install .NET SDK

```bash
# Check if .NET is installed
dotnet --version

# List installed SDKs
dotnet --list-sdks
```

### 2. Create Your First ASP.NET App

```bash
# Create a new Web API project
dotnet new webapi -n MyFirstAPI

# Navigate to the project
cd MyFirstAPI

# Run the application
dotnet run
```

### 3. Install Useful Tools

```bash
# Install EF Core tools globally
dotnet tool install --global dotnet-ef

# Install ASP.NET code generator
dotnet tool install --global dotnet-aspnet-codegenerator
```

## Learning Path

Follow this recommended order:

1. **Basics** - Start with fundamental concepts
2. **WebAPI** - Learn to build REST APIs
3. **EntityFramework** - Work with databases
4. **Authentication** - Implement security
5. **MVC** - Build full web applications
6. **Projects** - Apply everything in real projects

## Useful Commands

```bash
# Create new project
dotnet new [template] -n [ProjectName]

# Restore dependencies
dotnet restore

# Build project
dotnet build

# Run project
dotnet run

# Run tests
dotnet test

# Add NuGet package
dotnet add package [PackageName]
```

## Tips for Success

- ✅ Code along with tutorials
- ✅ Take notes on key concepts
- ✅ Build small projects to practice
- ✅ Read documentation regularly
- ✅ Join the community and ask questions
- ✅ Version control everything with Git

## Next Steps

1. Review the main README.md for repository structure
2. Start with the Basics folder
3. Follow the learning checklist in each folder
4. Document your progress in the Notes folder

Happy Learning! 🚀
