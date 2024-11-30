<div id="header" align="center">
  <img src="https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif" width="100"/>
</div>

# Employee Management API with SQL Server and Swagger Integration

<h3 align="center">A CRUD-based Employee Management API using ASP.NET Core, integrated with SQL Server and Swagger for seamless API management and documentation.</h3>

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=missvanshika09&label=Project%20views&color=0e75b6&style=flat" alt="missvanshika09" />
</p>

---

## 📝 Overview

This project provides a **RESTful API** for managing employee data using **ASP.NET Core** and **SQL Server**. It demonstrates:

- CRUD operations for managing employees.
- Integration with **Entity Framework Core** for database interaction.
- Swagger/OpenAPI for easy API testing and documentation.
- The **Repository Pattern** for a clean and scalable architecture.

---

## ✨ Features

- Full implementation of **CRUD operations** for employee management.
- SQL Server integration via **Entity Framework Core**.
- Swagger for **interactive API documentation**.
- Repository Pattern for clean, modular, and testable code.
- CORS policy for cross-origin support.

---

## ⚙️ Technologies Used

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
    <img src="https://swagger.io/img/assets/images/logo-styled.svg" alt="swagger" width="40" height="40"/>
  </a>
</p>

---

## 🚀 How to Run

### Step 1: Clone the repository

```bash
git clone https://github.com/username/repository.git
cd repository

        <!-- How to Run -->
        <div class="section">
            <h2 class="section-title">🚀 How to Run</h2>
            <ol>
                <li><strong>Clone the repository:</strong>
                    <pre><code>git clone https://github.com/username/repository.git
cd repository</code></pre>
                </li>
                <li><strong>Install dependencies:</strong>
                    <pre><code>Install-Package Microsoft.EntityFrameworkCore
Install-Package Microsoft.EntityFrameworkCore.SqlServer
Install-Package Microsoft.EntityFrameworkCore.Tools
Install-Package Microsoft.EntityFrameworkCore.Design</code></pre>
                </li>
                <li><strong>Configure the database:</strong>
                    <pre><code>{
   "ConnectionStrings": {
      "EmployeeDBConnection": "Data Source=(localdb)\\ProjectModels;Initial Catalog=DemoData;Integrated Security=True"
   }
}</code></pre>
                    Run migrations:
                    <pre><code>Add-Migration InitialCreate
Update-Database</code></pre>
                </li>
                <li><strong>Run the project:</strong>
                    <pre><code>dotnet run</code></pre>
                </li>
            </ol>
        </div>

        <!-- License -->
        <div class="footer">
            <p>💻 Built with ❤️ by missvanshika09 💻</p>
        </div>

    </div>

</body>
</html>
