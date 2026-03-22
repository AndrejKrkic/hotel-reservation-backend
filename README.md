# Hotel Reservation System - ASP.NET Backend

This is the backend service for the Hotel Reservation web application.

It provides RESTful APIs for managing users, rooms, reservations, and authentication.

The application is built using ASP.NET and Entity Framework, following clean architecture principles.

------------------------------------------------------------------------

## 🚀 Features

-   🔐 User authentication (Login/Register)
-   🏨 Room management
-   📅 Reservation system
-   👤 User profile management
-   🔄 CRUD operations for all entities
-   🛡️ Secure API endpoints

------------------------------------------------------------------------

## 🛠️ Tech Stack

- ASP.NET Core Web API (.NET 6+)
- Entity Framework Core
- SQL Server
- JWT Authentication
- Swagger / OpenAPI
- CORS policy setup for frontend communication
- LINQ

------------------------------------------------------------------------

## 📦 Installation & Setup

1. Clone the repository:

   ```git clone https://github.com/AndrejKrkic/hotel-reservation-backend.git```

2. Open the solution in Visual Studio or run from CLI.

3. Update the database connection string in appsettings.json:
"ConnectionStrings": {
  "DefaultConnection": "Server=YOUR_SERVER;Database=HotelBookingDB;Trusted_Connection=True;TrustServerCertificate=True;"
}

4. Apply migrations and create the database:
```dotnet ef database update```

5. Run the application: 
```dotnet run```

------------------------------------------------------------------------

## 📁 Project Structure

DTO/ - Data Transfer Objects used for communication between layers

Services/ - Business logic and application use cases

Data/ - Database context and Entity Framework configuration

Models/ - Domain entities representing core business data

Migrations/ - Database schema changes and versioning


------------------------------------------------------------------------

## 🔑 API Endpoints (Examples)

### Authentication

-   POST /api/auth/register
-   POST /api/auth/login

### Rooms

-   GET /api/rooms
-   POST /api/rooms
-   PUT /api/rooms/{id}
-   DELETE /api/rooms/{id}

### Reservations

-   GET /api/reservations
-   POST /api/reservations

------------------------------------------------------------------------
## 📚 What I Learned

- Designing and building RESTful APIs using ASP.NET Core

- Structuring a backend project using clean and maintainable architecture principles

- Working with Entity Framework Core for database access and data modeling

- Implementing CRUD operations and managing relational data

- Handling user authentication and authorization using JWT tokens

- Managing application configuration and environment settings

- Using LINQ for efficient data querying

- Debugging and testing API endpoints using Swagger and Postman

------------------------------------------------------------------------

## 🔗 Related Repositories

Frontend: https://github.com/AndrejKrkic/hotel-reservation-frontend.git

------------------------------------------------------------------------

## 📬 Contact

LinkedIn: https://www.linkedin.com/in/andrej-krkic-862805265/
