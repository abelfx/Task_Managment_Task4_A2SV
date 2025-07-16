# 📝 Task Management REST API (Go + Gin)

This project is a simple **Task Management REST API** built using **Go** and the **Gin Web Framework**. It supports full CRUD operations on tasks using an in-memory data store.

---

## 🚀 Features

- ✅ Create a new task
- ✅ Retrieve all tasks or a specific task by ID
- ✅ Update a task by ID
- ✅ Delete a task by ID
- ✅ In-memory storage (no database required)
- ✅ Clean, modular code structure

---

## 📂 Folder Structure
task_manager/
├── main.go # App entry point
├── controllers/ # HTTP handlers
│ └── task_controller.go
├── models/ # Data models
│ └── task.go
├── data/ # Business logic & data layer
│ └── task_service.go
├── router/ # Route configuration
│ └── router.go
├── docs/ # Documentation
│ └── api_documentation.md
└── go.mod

## 🛠️ Getting Started

### 1. Clone the repository

```
git clone https://github.com/your-username/task_manager.git
cd task_manager
go run main.go
```
🔍 API Documentation
For full details on how to use the API (request/response formats), go to:

📄 docs/api_documentation.md
