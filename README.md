# Learnify #

### 📚 Project :  E-Learning Management System (Backend)

### 📂 Repository Links: [Learnify Backend](https://github.com/Nabila-Nabil/Learnify-backend-E-Learning-Management-System-api) , [Leanify with Angular](https://github.com/Nabila-Nabil/Learnify-Frontend-e-learning-management-system) 


### 📜 Project Description:
A comprehensive backend system for an e-learning management platform, enabling seamless course management, user authentication, and content delivery.

### 🛠 Technologies Used:
**1-Entity Framework Core**: ORM for database operations.

**2-SQL Server**: Database management system.

**3-ASP.NET Core Identity**: For authentication and authorization.

**4-JWT**: For token-based authentication.

**5-AutoMapper**: For object-object mapping.

**6-Repository Pattern**: For data access abstraction.

**7-Dependency Injection**: For managing dependencies.

**8-DTOs**: For data transfer between layers.


### 🌟 Features: 
- User authentication and role management
- Course creation and management
- Content delivery and tracking
- Secure API endpoints

### 🚀 Setup Instructions:
1. **Clone the repository:**
 
   `
    git clone https://github.com/Nabila-Nabil/Learnify-e-learning-management-system
    `

2. **Navigate to the project directory:**

    `
    cd Learnify-e-learning-management-system
    `

3. **Install dependencies:**
   
    `
    dotnet restore
    `

4. **Update the database connection string in `appsettings.json`:**
   
   ```
    "ConnectionStrings": {
        "DefaultConnection": "Your-Connection-String-Here"
    }
    ```

5. **Run the database migrations:**
   
   ```bash
    dotnet ef database update
    ```
6. **Run the application:**
  
    ```bash
    dotnet run
    ```

