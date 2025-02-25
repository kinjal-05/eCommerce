<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>eCommerce Platform - ASP.NET Core MVC</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            padding: 20px;
            max-width: 900px;
            margin: auto;
        }
        h1, h2, h3 {
            color: #0056b3;
        }
        .section {
            background: #fff;
            padding: 20px;
            margin: 10px 0;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        ul {
            list-style: none;
            padding: 0;
        }
        li {
            margin: 5px 0;
        }
        .icon {
            color: #28a745;
            font-weight: bold;
        }
        .command {
            background: #e3e3e3;
            padding: 5px 10px;
            border-radius: 5px;
            font-family: monospace;
        }
    </style>
</head>
<body>
    <h1>🌟 eCommerce Platform - ASP.NET Core MVC</h1>
    
    <div class="section">
        <h2>📌 Purpose</h2>
        <p>This project is a web-based eCommerce platform built using ASP.NET Core MVC with Entity Framework (EF) Core for database management.</p>
    </div>
    
    <div class="section">
        <h2>🚀 Features</h2>
        <ul>
            <li><span class="icon">✅</span> Role-based Authorization</li>
            <li><span class="icon">✅</span> Entity Framework Core for database operations</li>
            <li><span class="icon">✅</span> State Management & Sessions</li>
            <li><span class="icon">✅</span> CRUD Operations</li>
            <li><span class="icon">✅</span> Order Management System</li>
            <li><span class="icon">✅</span> Email Notifications with SendGrid</li>
            <li><span class="icon">✅</span> Secure Payment with Stripe</li>
        </ul>
    </div>
    
    <div class="section">
        <h2>🛠 Technologies Used</h2>
        <ul>
            <li>ASP.NET Core MVC</li>
            <li>Entity Framework Core</li>
            <li>Microsoft SQL Server</li>
            <li>Bootstrap 5 / CSS</li>
            <li>ASP.NET Core Identity</li>
            <li>SendGrid for Emails</li>
            <li>Stripe for Payments</li>
        </ul>
    </div>
    
    <div class="section">
        <h2>🏗️ How to Run the Project</h2>
        <h3>🔧 Prerequisites</h3>
        <ul>
            <li>.NET SDK</li>
            <li>SQL Server</li>
            <li>Visual Studio</li>
            <li>Entity Framework Core CLI: <span class="command">dotnet tool install --global dotnet-ef</span></li>
            <li>SendGrid & Stripe Accounts</li>
        </ul>
        
        <h3>📌 Steps</h3>
        <ul>
            <li>1️⃣ Navigate to project folder: <span class="command">cd path/to/eCommerceAsp.NET_CORE</span></li>
            <li>2️⃣ Configure <strong>appsettings.json</strong> with your database & API keys.</li>
            <li>3️⃣ Apply migrations: <span class="command">dotnet ef database update</span></li>
            <li>4️⃣ Build the project: <span class="command">dotnet build</span></li>
            <li>5️⃣ Run the application: <span class="command">dotnet run</span></li>
            <li>6️⃣ Open browser and navigate to: <span class="command">http://localhost:5000</span></li>
        </ul>
    </div>
    
    <div class="section">
        <h2>📩 Need Help?</h2>
        <p>If you encounter any issues, feel free to open an issue on GitHub!</p>
    </div>
</body>
</html>
