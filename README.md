# Contacts Manager (MVC Project)

## 📌 Overview
The **Contacts Manager** is a web application built with **ASP.NET MVC** that provides full CRUD operations for managing contacts efficiently. The project follows **Clean Architecture** principles and includes authentication, export/import functionality, and unit testing.

## ✨ Features
- **CRUD Operations**: Create, Read, Update, and Delete contacts.
- **Search & Sorting**: Search contacts by name or other details, with sorting functionality.
- **Export & Import**:
  - Export contacts to **PDF** and **Excel**.
  - Bulk import contacts via **Excel**.
- **Authentication**:
  - User registration, login, and logout with **ASP.NET Identity**.
- **Testing**:
  - Unit Testing with **xUnit** and **Moq**.
  - Integration Testing for API and UI flows.

## 🏗️ Technology Stack
- **Frontend**: ASP.NET MVC
- **Backend**: ASP.NET Core
- **Database**: SQL Server
- **Authentication**: ASP.NET Identity
- **Testing**: xUnit, Moq
- **Architecture**: Clean Architecture

## 🚀 Getting Started
### Prerequisites
- .NET SDK (>= .NET 6)
- SQL Server

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/ContactsManagerSolution.git
   ```
2. Navigate to the project directory:
   ```sh
   cd ContactsManagerSolution
   ```
3. Restore dependencies:
   ```sh
   dotnet restore
   ```
4. Update **appsettings.json** with your database connection string.

### Running the Application
1. Apply database migrations:
   ```sh
   dotnet ef database update
   ```
2. Run the application:
   ```sh
   dotnet run
   ```
3. Open your browser and navigate to:
   ```sh
   http://localhost:5000
   ```

## 🎯 Contribution
Contributions are welcome! Feel free to open issues or submit pull requests.

## 📜 License
This project is licensed under the MIT License.

## 📞 Contact
For any questions, reach out or open an issue in the repository.

Happy Coding! 🚀
