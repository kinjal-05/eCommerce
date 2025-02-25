# <span style="color:#3498db; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 2.5em;">eCommerce Platform</span> 

📌 <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.2em;">**Project Overview**</span>

This project is a web-based eCommerce platform built using ASP.NET Core MVC with Entity Framework (EF) Core for database management. It provides a robust role-based authorization system, allowing admins, producers, and consumers to interact with the system based on their roles.

✨ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.5em;">**Features**</span>

🔐 <span style="color:#2ecc71; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**Role-based Authorization**</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">**Producers:** Manage product catalogs (add, update, delete products).</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">**Consumers:** Place orders, manage profiles, and view products.</span>

🗄️ <span style="color:#2ecc71; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**Entity Framework Core**</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">ORM functionalities with migrations for smooth schema updates.</span>

🌍 <span style="color:#2ecc71; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**State Management & Sessions**</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">User authentication and authorization using sessions.</span>

🛒 <span style="color:#2ecc71; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**CRUD Operations**</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Full Create, Read, Update, Delete functionality for products & profiles.</span>

📦 <span style="color:#2ecc71; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**Order Management Workflow**</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Pending → Confirmed → Dispatched → Finished</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Consumers can also cancel an order.</span>

📧 <span style="color:#2ecc71; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**Email Notifications**</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Order status updates via SendGrid.</span>

📱 <span style="color:#2ecc71; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**Responsive UI**</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Built using Bootstrap 5 for a seamless experience across devices.</span>

🛂 <span style="color:#2ecc71; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**Authentication**</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Managed using ASP.NET Core Identity.</span>

💳 <span style="color:#2ecc71; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**Payment Integration**</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Powered by Stripe.</span>

🛠️ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.5em;">**Technologies Used**</span>

*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">ASP.NET Core MVC</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Entity Framework Core</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Microsoft SQL Server</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Bootstrap 5 / CSS</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Session Management</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">ASP.NET Core Identity</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Stripe (Payment Gateway)</span>
*   <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">SendGrid (Email Notifications)</span>

🚀 <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.5em;">**Prerequisites**</span>

Before running the project, ensure the following tools are installed:

🏗️ <span style="color:#e74c3c; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**.NET SDK**</span> <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">(matching your project version)</span>
🗄️ <span style="color:#e74c3c; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**SQL Server**</span> <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">(or any configured database)</span>
🖥️ <span style="color:#e74c3c; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**Visual Studio**</span> <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">(or any IDE with .NET Core support)</span>
🛠️ <span style="color:#e74c3c; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**Entity Framework Core CLI**</span> <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">(installed via .NET CLI):</span>
    <code style="font-family: 'Courier New', Courier, monospace;">dotnet tool install --global dotnet-ef</code>
📩 <span style="color:#e74c3c; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.3em;">**SendGrid Account**</span> <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">(for email notifications)</span>

⚙️ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.5em;">**Setup & Installation**</span>

1️⃣ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">**Clone the Repository**</span>

```bash
git clone https://github.com/yourusername/ecommerce-platform.git
cd ecommerce-platform
2️⃣ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Configure the Database</span>

Open appsettings.json and ensure the connection string is correctly set:

json
{
  "ConnectionStrings": {
    "DefaultConnection": "Server=(localdb)\\mssqllocaldb;Database=your_db;Trusted_Connection=True;MultipleActiveResultSets=true"
  },
  "Stripe": {
    "SecretKey": "your_stripe_secret_key",
    "PublishableKey": "your_stripe_publishable_key"
  },
  "SendGrid": {
    "ApiKey": "your_sendgrid_api_key"
  }
}
3️⃣ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Apply Migrations</span>

bash
dotnet ef database update
<span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">This command sets up the database schema.</span>

4️⃣ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Build the Project</span>

bash
dotnet build
5️⃣ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Run the Application</span>

bash
dotnet run
6️⃣ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Open in Browser</span>

<span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">After running the application, visit the URL shown in the terminal (e.g., </span><code style="font-family: 'Courier New', Courier, monospace;">http://localhost:5000</code><span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">).</span>

📜 <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.5em;">License</span>

<span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">This project is MIT Licensed. Feel free to modify and use it as needed!</span>

🤝 <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.5em;">Contributing</span>

<span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Contributions are welcome! Follow these steps:</span>

<span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Fork the repository.</span>
<span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Create a new branch (</span><code style="font-family: 'Courier New', Courier, monospace;">feature-xyz</code><span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">).</span>
<span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Commit your changes.</span>
<span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Push the branch and create a Pull Request.</span>
📬 <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; font-size: 1.5em;">Contact</span>

<span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">For any queries, reach out via:</span>

📧 <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Email: your-email@example.com</span> 🐙 <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">GitHub: yourusername</span> 🌐 <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">Website: yourwebsite.com</span>

🌟 <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">If you like this project, please give it a ⭐ on GitHub!</span>
