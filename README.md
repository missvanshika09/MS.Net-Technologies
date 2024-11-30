<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Management API with Swagger Integration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }
        #header {
            text-align: center;
            margin-top: 20px;
        }
        h1 {
            text-align: center;
            color: #0078d7;
        }
        h3 {
            text-align: center;
            color: #555;
            margin-bottom: 20px;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
        }
        .section-title {
            font-size: 1.5em;
            color: #0078d7;
            margin-top: 20px;
        }
        pre, code {
            background: #eee;
            padding: 10px;
            border-radius: 5px;
            display: block;
        }
        a {
            color: #0078d7;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        .technologies img {
            margin-right: 10px;
        }
        .footer {
            text-align: center;
            margin-top: 40px;
            color: #777;
        }
    </style>
</head>
<body>

    <!-- Header -->
    <div id="header">
        <img src="https://media.giphy.com/media/26tn33aiTi1jkl6H6/giphy.gif" width="100"/>
    </div>

    <!-- Title -->
    <h1>Employee Management API with SQL Server and Swagger Integration</h1>
    <h3>A CRUD-based Employee Management API using ASP.NET Core, integrated with SQL Server and Swagger for seamless API management and documentation.</h3>

    <div class="container">

        <!-- Overview Section -->
        <div class="section">
            <h2 class="section-title">📝 Overview</h2>
            <p>
                This project provides a <strong>RESTful API</strong> for managing employee data using <strong>ASP.NET Core</strong> and <strong>SQL Server</strong>. It demonstrates:
            </p>
            <ul>
                <li>CRUD operations for managing employees.</li>
                <li>Integration with Entity Framework Core for database interaction.</li>
                <li>Swagger/OpenAPI for easy API testing and documentation.</li>
                <li>The Repository Pattern for a clean and scalable architecture.</li>
            </ul>
        </div>

        <!-- Features Section -->
        <div class="section">
            <h2 class="section-title">✨ Features</h2>
            <ul>
                <li>Full implementation of CRUD operations for employee management.</li>
                <li>SQL Server integration via Entity Framework Core.</li>
                <li>Swagger for interactive API documentation.</li>
                <li>Repository Pattern for clean, modular, and testable code.</li>
                <li>CORS policy for cross-origin support.</li>
            </ul>
        </div>

        <!-- Technologies Used -->
        <div class="section">
            <h2 class="section-title">⚙️ Technologies Used</h2>
            <p class="technologies">
                <a href="https://dotnet.microsoft.com/" target="_blank"><img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/dot-net/dot-net-original-wordmark.svg" alt="dotnet" width="40" height="40"/></a>
                <a href="https://learn.microsoft.com/en-us/ef/" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/1/1e/Entity_Framework.png" alt="ef-core" width="40" height="40"/></a>
                <a href="https://www.microsoft.com/en-us/sql-server" target="_blank"><img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="sqlserver" width="40" height="40"/></a>
                <a href="https://swagger.io/" target="_blank"><img src="https://swagger.io/img/assets/images/logo-styled.svg" alt="swagger" width="40" height="40"/></a>
            </p>
        </div>

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
