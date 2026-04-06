# 📝 Task Management Application (Angular + .NET Core API)

---

## 📌 Project Description
This is a Full Stack Task Management Application built using **Angular (Frontend)** and **.NET Core Web API (Backend)**.

The application allows users to perform CRUD operations such as:
- Add tasks
- View tasks
- Edit tasks
- Delete tasks
- Mark tasks as completed

---

## 🚀 Features

### 🔹 Frontend (Angular)
- Display tasks in a table
- Add new task
- Edit existing task
- Delete task
- Mark task as completed (checkbox)
- Responsive UI using Bootstrap

### 🔹 Backend (.NET Core API)
- RESTful API with CRUD operations
- Proper HTTP status codes
- Basic validation (Title required)
- Uses In-Memory Database / Entity Framework Core

---

## 🛠️ Technologies Used

### Frontend
- Angular
- TypeScript
- HTML
- CSS
- Bootstrap

### Backend
- .NET Core Web API
- C#
- Entity Framework Core / In-Memory DB

---

## 🔗 API Endpoints

| Method | Endpoint           | Description         |
|--------|-------------------|---------------------|
| GET    | /api/tasks        | Get all tasks       |
| GET    | /api/tasks/{id}   | Get task by ID      |
| POST   | /api/tasks        | Create new task     |
| PUT    | /api/tasks/{id}   | Update task         |
| DELETE | /api/tasks/{id}   | Delete task         |

---

## ▶️ How to Run the Project

### 🔹 Backend Setup (.NET Core API)

1. Open backend project in Visual Studio / VS Code  
2. Restore dependencies  
3. Run the API  


bash
dotnet run


