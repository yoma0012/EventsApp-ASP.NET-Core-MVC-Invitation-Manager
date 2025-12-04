# 🎉 EventsApp – ASP.NET Core MVC Invitation Manager

EventsApp is a full-stack ASP.NET Core MVC application that allows users to create parties, manage invitations, track guest responses, and handle authentication/authorization using Identity.  
This project demonstrates real-world skills including MVC architecture, role-based security, EF Core data modeling, and unit testing.

---

## 🚀 Features

### 👤 Authentication & Authorization
- ASP.NET Core Identity integration  
- User registration and login  
- Role-based access (Admin / Regular User)  
- Secure ownership checks for Parties and Invitations  

### 🎉 Party Management
- Create, edit, view party details  
- Soft delete + undo delete (Admin only)  
- Party statistics dashboard (Sent, Accepted, Declined, Not Sent)

### 📨 Invitations Workflow
- Add invitations to a party  
- Send invitations  
- Guest login triggers a popup for Accept/Decline  
- Invitation status saved and updated in real time  

### 🗄️ Data & Architecture
- EF Core with SQLite  
- Migrations enabled  
- Clean MVC separation (Models, Views, Controllers)  
- ViewModels for presentation logic (`PartyStatsViewModel`)

### 🧪 Unit Tests
Includes simple xUnit tests:
- Invitation status updates  
- Party statistics calculations  

---

## 🏗️ Project Architecture

Browser → Controllers → Services / EF Core → SQLite Database
↑ ↓
Views (Razor UI) ←────


---

## 📦 Technologies Used
- **ASP.NET Core 8 MVC**
- **Entity Framework Core**
- **ASP.NET Identity**
- **SQLite**
- **Bootstrap 5**
- **xUnit for testing**
- **Rider / Visual Studio / .NET CLI**

---

## 🧰 Setup Instructions

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/EventsApp.git
   cd EventsApp
2. Apply migrations: dotnet ef database update
3. Run the application:dotnet run
4. Login using the seeded admin:
   Email: admin@admin.com
   Password: Admin123!

---



