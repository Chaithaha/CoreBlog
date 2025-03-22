# School Database Project

This ASP.NET Core project manages teachers in a school database with both API endpoints (/api/teachers and /api/teachers/{id}) and web pages (/teacher/list and /teacher/show/{id}). The project includes models (SchoolDbContext.cs, Teacher.cs), controllers (TeacherAPIController.cs, TeacherPageController.cs), and views (List.cshtml, Show.cshtml) to display teacher information. To run, update the database connection in appsettings.json and use "dotnet run" command. Currently implements Read functionality, with Create, Update, and Delete to be added later.
