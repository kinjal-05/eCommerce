<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>eCommerce Platform - ASP.NET Core MVC</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            color: #333;
            margin: 20px;
            padding: 20px;
        }
        h1, h2, h3 {
            color: #2c3e50;
        }
        .container {
            max-width: 900px;
            margin: auto;
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        code {
            background: #eee;
            padding: 2px 5px;
            border-radius: 5px;
        }
        .highlight {
            background: #e7f4ff;
            padding: 10px;
            border-left: 5px solid #3498db;
            margin: 10px 0;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>🌟 eCommerce Platform - ASP.NET Core MVC</h1>
        
        <h2>📌 Purpose</h2>
        <p>This project is a web-based eCommerce platform built using ASP.NET Core MVC with Entity Framework (EF) Core for database management.</p>
        
        <h2>🚀 Features</h2>
        <ul>
            <li><strong>Role-based Authorization</strong>: Admin, Producers, Consumers</li>
            <li><strong>Entity Framework Core</strong>: Efficient ORM, database migrations</li>
            <li><strong>State Management & Sessions</strong>: Secure authentication using ASP.NET Core Identity</li>
            <li><strong>CRUD Operations</strong>: Full product and profile management</li>
            <li><strong>Order Management</strong>: Track order statuses (Pending, Confirmed, Dispatched, Finished, Canceled)</li>
            <li><strong>Email Notifications</strong>: SendGrid integration for order updates</li>
            <li><strong>Payment Processing</strong>: Stripe integration for secure transactions</li>
        </ul>
        
        <h2>🛠 Technologies Used</h2>
        <ul>
            <li>ASP.NET Core MVC</li>
            <li>Entity Framework Core</li>
            <li>Microsoft SQL Server</li>
            <li>Bootstrap 5 / CSS</li>
            <li>ASP.NET Core Identity</li>
            <li>SendGrid for emails</li>
            <li>Stripe for payments</li>
        </ul>
        
        <h2>🏗️ How to Run the Project</h2>
        <h3>🔧 Prerequisites</h3>
        <ul>
            <li>.NET SDK</li>
            <li>SQL Server</li>
            <li>Visual Studio / VS Code</li>
            <li>Entity Framework CLI: <code>dotnet tool install --global dotnet-ef</code></li>
            <li>SendGrid & Stripe accounts</li>
        </ul>
        
        <h3>📌 Steps to Run the Project</h3>
        <ol>
            <li><strong>Navigate to Project Folder:</strong> <code>cd path/to/eCommerceAsp.NET_CORE</code></li>
            <li><strong>Configure Database & API Keys</strong></li>
        </ol>
        <div class="highlight">
            <pre><code>{
  "ConnectionStrings": {
    "DefaultConnection": "Server=YOUR_SERVER_NAME;Database=eCommerceDB;Trusted_Connection=True;"
  },
  "Stripe": {
    "SecretKey": "your_stripe_secret_key",
    "PublishableKey": "your_stripe_publishable_key"
  },
  "SendGrid": {
    "ApiKey": "your_sendgrid_api_key"
  }
}</code></pre>
        </div>
        <ol start="3">
            <li><strong>Apply Migrations:</strong> <code>dotnet ef database update</code></li>
            <li><strong>Build the Project:</strong> <code>dotnet build</code></li>
            <li><strong>Run the Application:</strong> <code>dotnet run</code></li>
            <li><strong>Open in Browser:</strong> Check terminal output for <code>http://localhost:5000</code></li>
        </ol>
        
        <h3>📩 Need Help?</h3>
        <p>If you run into any issues, feel free to reach out or open an issue on GitHub!</p>
        <h2>🛒 Happy Coding & Enjoy Building Your eCommerce Platform! 🚀</h2>
    </div>
</body>
</html>
