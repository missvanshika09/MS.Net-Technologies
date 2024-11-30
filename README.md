<div id="header" align="center">
  <img src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" width="100"/>
</div>

<h1 align="center">Member Management API with Swagger Integration</h1>

  
<h3 align="center">This project is a simple Member Management API built using ASP.NET Core. It demonstrates the use of:

<br>CRUD operations (Create, Read, Update, Delete) for managing members.</br>
<br>Dependency Injection (DI) for service management.</br>
<br>Swagger integration for generating API documentation.</br>
<br>A basic in-memory data repository simulating a database.</br></h3>

<h1 align="center">Employee Management API with SQL Server and Swagger Integration</h1>
  
<h3 align="center">A CRUD-based Employee Management API using ASP.NET Core, integrated with SQL Server and Swagger for seamless API management and documentation.</h3>

<p align="left"> 
  <img src="https://komarev.com/ghpvc/?username=missvanshika09&label=Project%20views&color=0e75b6&style=flat" alt="missvanshika09" />
</p>

- 🚀 **How to Run**  
  1. Clone the repository:  
     ```bash
     git clone https://github.com/username/repository.git
     cd repository
     ```
  2. Install dependencies:
     ```bash
     Install-Package Microsoft.EntityFrameworkCore
     Install-Package Microsoft.EntityFrameworkCore.SqlServer
     Install-Package Microsoft.EntityFrameworkCore.Tools
     Install-Package Microsoft.EntityFrameworkCore.Design
     ```
  3. Configure the database in `appsettings.json`:
     ```json
     "ConnectionStrings": {
       "EmployeeDBConnection": "Data Source=(localdb)\\ProjectModels;Initial Catalog=DemoData;Integrated Security=True"
     }
     ```
  4. Run migrations:
     ```bash
     Add-Migration InitialCreate
     Update-Database
     ```
  5. Start the project:  
     ```bash
     dotnet run
     ```

- 🌐 **API Endpoints**  
  - **GET** `/api/Employee`: Fetch all employees.  
  - **GET** `/api/Employee/{id}`: Fetch an employee by ID.  
  - **POST** `/api/Employee`: Add a new employee.  
  - **PUT** `/api/Employee/{id}`: Update an employee.  
  - **DELETE** `/api/Employee/{id}`: Delete an employee.  

---

<h3 align="left">Technologies Used:</h3>
<p align="left">
  <a href="https://dotnet.microsoft.com/" target="_blank" rel="noreferrer"> 
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/> 
  </a>
  <a href="https://learn.microsoft.com/en-us/ef/" target="_blank" rel="noreferrer"> 
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Entity_Framework.png" alt="ef-core" width="40" height="40"/> 
  </a>
  <a href="https://www.microsoft.com/en-us/sql-server" target="_blank" rel="noreferrer"> 
    <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="sqlserver" width="40" height="40"/> 
  </a>
  <a href="https://swagger.io/" target="_blank" rel="noreferrer"> 
    <img src="[https://swagger.io/img/assets/images/logo-styled.svg](https://www.google.com/search?q=swagger.io+image&oq=swagger.io+image&gs_lcrp=EgZjaHJvbWUyBggAEEUYOTIICAEQABgWGB4yCggCEAAYgAQYogQyCggDEAAYgAQYogQyCggEEAAYgAQYogQyCggFEAAYgAQYogQyCggGEAAYgAQYogTSAQkxMDE1NmowajSoAgCwAgE&sourceid=chrome&ie=UTF-8#imgrc=k_bVmcCBIx-k8M&imgdii=cFd1pATom6mbsM)" alt="swagger" width="40" height="40"/> 
  </a>
</p>

---

<h3 align="left">📜 License</h3>
This project is open-source and licensed under the MIT License.

<p align="center">💻 Built with ❤️ by missvanshika09 💻</p>
