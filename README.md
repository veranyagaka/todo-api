# 📝 To-Do List API (CRUD App)

This is a simple RESTful API for a To-Do list application built using **Node.js**, **Express**, and **MongoDB**. It supports full CRUD operations (Create, Read, Update, Delete) for managing tasks.

## Features

- Add new to-do items
- View all to-dos or a single to-do
- Update to-do details
- Delete completed or unwanted tasks

## 📚 Technologies Used

- Node.js
- Express 
- MongoDB
- dotenv

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/veranyagaka/todo-api.git
cd todo-api
```
### 2. Install dependencies
```bash
npm install
```

### 3. Set up environment variables

Create a .env file - sample file is provided

### 4. Start MonogDB

```bash
sudo systemctl start mongodb

```

### 5. Run the app
```bash
npm run dev
```

### Sample Todo: json - use curl or Postman
```json
{
  "title": "Buy groceries",
  "description": "Milk, Eggs, Bread, Fruits",
  "completed": false
}
```

### Postman Documentation: https://documenter.getpostman.com/view/30947494/2sB2x3oth7