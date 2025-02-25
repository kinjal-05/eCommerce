# 🛒 eCommerce Platform - ASP.NET Core MVC  

## 📌 Purpose  
This project is a **web-based eCommerce platform** built using **ASP.NET Core MVC** with **Entity Framework (EF) Core** for database management.  
The system offers **robust user role management**, including:  

- **👨‍💼 Admin:** Manages users, orders, and platform settings.  
- **🏭 Producers:** Manage product catalogs (add, update, delete products).  
- **🛍️ Consumers:** Place orders, manage profiles, and view products.  

The platform supports **product management, user profile handling, and order workflows** with **CRUD operations** across all roles.  

---

## 🚀 Features  

### ✅ **Role-based Authorization**  
- **Producers**: Manage product catalogs (add, update, delete products).  
- **Consumers**: Place orders, manage profiles, and view products.  

### ✅ **Entity Framework Core**  
- Database operations are managed through **EF Core**, providing **ORM functionalities**.  
- Uses **Migrations** to ensure smooth schema updates.  

### ✅ **State Management & Sessions**  
- User authentication and authorization managed using **sessions**.  
- Different session states for **logged-in and guest users**.  

### ✅ **CRUD Operations**  
- Products and **user profiles** support full **Create, Read, Update, and Delete (CRUD)** operations.  
- **Search & Filter** products by **name, date, and price**.  

### ✅ **Order Management System**  
Orders progress through the following statuses:  
- 🕒 **Pending**: Booked but payment pending.  
- ✅ **Confirmed**: Payment received.  
- 🚚 **Dispatched**: Order in transit.  
- 🎉 **Finished**: Delivered and payment completed.  
- ❌ **Canceled**: Consumers can cancel orders.  

### ✅ **🔔 Notifications**  
- 📧 **Email notifications** for order status updates using **SendGrid**.  

### ✅ **💳 Payment Integration**  
- Secure **Stripe** payment gateway.  

### ✅ **📱 Responsive Design**  
- Built with **Bootstrap 5 & CSS** for a seamless UI experience.  

### ✅ **🔒 Security & Authentication**  
- **ASP.NET Core Identity** for secure authentication.  
- **Composite keys** applied to `UserID` and `Email` to ensure **data integrity**.  

---

## 🛠 Technologies Used  

| Technology  | Description |
|------------|------------|
| **ASP.NET Core MVC** | Backend framework for handling requests |
| **Entity Framework Core** | ORM for database interactions |
| **Microsoft SQL Server** | Database management |
| **Bootstrap 5 / CSS** | Frontend UI styling |
| **Session Management** | User state handling |
| **ASP.NET Core Identity** | Secure authentication |
| **Stripe** | Payment processing |
| **SendGrid** | Email notifications |

---

## 🔧 Prerequisites  

Before running the project, ensure you have the following installed:  

- ✅ [.NET SDK](https://dotnet.microsoft.com/download) (matching your project version)  
- ✅ [SQL Server](https://www.microsoft.com/en-us/sql-server/sql-server-downloads) (or any configured database)  
- ✅ [Visual Studio](https://visualstudio.microsoft.com/) (or any IDE with .NET Core support)  
- ✅ **Entity Framework Core CLI:**  
  ```sh
  dotnet tool install --global dotnet-ef

2️⃣ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">**Configure the Database**</span>

Open `appsettings.json` and ensure the connection string and API keys are correctly set:
```json
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

```sh
3️⃣ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">**Apply Migrations**</span>

dotnet ef database update

```sh
4️⃣ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">**Build the Project**</span>
dotnet build

```sh
5️⃣ <span style="font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;">**Run the Application**</span>
dotnet run
