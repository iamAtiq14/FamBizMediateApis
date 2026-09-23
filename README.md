# Online Mediation for Family Business

[![.NET Core Web API](https://img.shields.io/badge/.NET_Core_Web_API-512BD4?style=flat&logo=dotnet&logoColor=white)](#)
[![Angular](https://img.shields.io/badge/Angular_16-DD0031?style=flat&logo=angular&logoColor=white)](#)
[![Entity Framework Core](https://img.shields.io/badge/Entity_Framework_Core-512BD4?style=flat&logo=dotnet&logoColor=white)](#)
[![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat&logo=microsoft-sql-server&logoColor=white)](#)
[![JWT Authentication](https://img.shields.io/badge/JWT_Authentication-000000?style=flat&logo=json-web-tokens&logoColor=white)](#)

**Repository:** [FamBizMediateApis](https://github.com/iamAtiq14/FamBizMediateApis)

## Project Overview
Online Mediation for Family Business is a final year university project. It is a secure web platform designed to facilitate family business operations, focusing on mediation, performance tracking, and project management. 

## Features
- **Performance Appraisal:** Track and evaluate employee performance.
- **Challenge Assessment:** Tools to assess and mediate business challenges.
- **Profile System:** Comprehensive user profiling.
- **Project Management:** Manage projects effectively within the family business context.
- **Task-Based Performance:** Granular tracking of performance based on tasks.
- **Employee Portal:** A dedicated portal for employees to access resources and tasks.
- **Analytics Dashboard:** Visual representation of key metrics and data.

## Tech Stack
- **Backend:** ASP.NET Core 6 Web API
- **Frontend:** Angular 16
- **Database ORM:** Entity Framework Core
- **Database:** SQL Server
- **Security:** JWT Authentication

## Architecture Overview
The application follows a client-server architecture. The backend is powered by a robust ASP.NET Core Web API, providing secure, RESTful endpoints protected by JWT authentication. Data persistence is handled via Entity Framework Core interacting with a SQL Server database. The client-side is a responsive Single Page Application (SPA) built with Angular 16.

## Getting Started

### Prerequisites
- .NET 6 SDK or later
- Node.js and npm (for Angular)
- SQL Server

### Backend Setup
1. Clone the repository.
2. Navigate to the API project directory.
3. Update the database connection string in `appsettings.json`.
4. Run Entity Framework migrations to update the database: `dotnet ef database update`
5. Run the application: `dotnet run`

### Frontend Setup
1. Navigate to the client app directory.
2. Install dependencies: `npm install`
3. Start the development server: `ng serve`
4. Access the application at `http://localhost:4200`

## Project Structure
- `/src`
  - `/API` - Controllers and API configurations
  - `/Core` - Domain models and interfaces
  - `/Infrastructure` - Data access and EF Core DbContext
  - `/ClientApp` - Angular 16 frontend application

## API Endpoints Section
*(Generic Overview)*
- `POST /api/auth/login` - Authenticate users and issue JWTs
- `GET /api/projects` - Retrieve projects
- `POST /api/projects` - Create a new project
- `GET /api/employees/{id}` - Retrieve employee profiles
- `GET /api/analytics` - Fetch dashboard data

## Contributing
As an academic project, contributions are generally closed, but suggestions and feedback are welcome.

## License
This project is for educational/portfolio purposes.
