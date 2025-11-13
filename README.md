📚 MiniCinemaApp – EF Core in ASP.NET Core Exercise

This project is a training exercise for students who are beginning with Entity Framework Core and ASP.NET Core MVC.
The application provides a small, clean skeleton with hardcoded data, empty services, and unfinished controllers, allowing students to focus on database queries and CRUD logic.

🎯 Exercise Goals

Students will practice:

Setting up EF Core in an ASP.NET Core MVC project

Creating and configuring a DbContext

Writing LINQ queries to the database

Implementing CRUD operations inside Services

Connecting Controllers to Services

Importing data from JSON and XML

Displaying database results through Views

Understanding the ASP.NET MVC folder structure

🏗️ Project Structure
Controllers/        → Controllers for Movies, Watchlist, Import
Data/               → DbContext + configuration
DataSets/           → Files for seeding (JSON, XML)
Models/             → Entity classes
ViewModels/         → ViewModels for UI binding
Services/           → Empty services students must implement
Views/              → Basic views (Movies, Watchlist, Import)
wwwroot/            → Static files (CSS, JS)

📦 What Is Already Done

✔ ASP.NET Core MVC skeleton
✔ Simple layout + navigation
✔ Hardcoded placeholder data
✔ Empty Services prepared for implementation
✔ Controllers reference the Service layer
✔ Basic views for Movies, Watchlist, and Import
✔ JSON and XML files prepared for import
✔ Cleaned JS files (only site.js kept)

🧪 What Students Must Do

1️⃣ Implement EF Core

Create the models

Configure relationships

Set up AppDbContext

Run migrations

Seed the database (optional)

2️⃣ Implement Services

Fill in logic for Movies, Watchlist, and Import

Write LINQ queries

Return ViewModels

3️⃣ Connect Controllers → Services

Replace hardcoded data

Add async database calls

4️⃣ Implement Import functionality

Import Movies from JSON

Import Movies from XML

5️⃣ Update Views

Display real DB data

Show lists, details, and watchlist items

🚀 How to Start the Project

Clone the project:

git clone https://github.com/KTsaneff/EFCore_in_ASP_exercise.git


Open MoviesApp.sln in Visual Studio

Update appsettings.json with your SQL Server connection string

Create database + migrations:

Add-Migration Initial
Update-Database


Run the project (F5)

📥 Importing Data

Navigate to:

/Import


There you will find two buttons:

Import Movies (JSON)

Import Movies (XML)

The logic is empty → students must implement it.

🧑‍🏫 Used In: EF Core + ASP.NET Core Lab Exercise

This repository is designed for classroom use.
Feel free to fork, practice, and extend it.

👨‍💻 Author

Krassy Tsaneff (KTsaneff)
SoftUni • Educator • ASP.NET Developer
