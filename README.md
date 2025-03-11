# Clean Architecture Project
This project follows Clean Architecture principles to ensure scalability, maintainability, and testability.

# Project Structure

```bash
src/
️️️️ CleanArchitecture.Application/   # Application logic (Use Cases, Services)
️️️️ CleanArchitecture.Domain/        # Core domain models and business rules
️️️️ CleanArchitecture.Infrastructure/ # Data persistence, APIs, external services
️️️️ CleanArchitecture.WebUI/          # User interface (REST API, Web App)
️️ CloudArchitecture.sln             # Solution file
️️ .gitignore                        # Git ignore rules
️️ .dockerignore                     # Docker ignore rules
️️ README.md                         # Project documentation
```

## Getting Started

- NET SDK (latest version recommended)
- Docker (optional for containerization)
- SQL Server/PostgreSQL (if applicable)

## Installation & Setup
- Clone the repository
```bash
git clone <repository-url>
cd CloudArchitecture
```
- Restore dependencies
```bash
dotnet restore
```
- Build the solution
```bash
dotnet build
```
- Run the application
```bash
dotnet run --project src/CleanArchitecture.WebUI
```