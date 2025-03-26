# 📌 PERN Todo App
A full-stack **PERN (PostgreSQL, Express, React, Node.js)** to-do application with CRUD functionality.

## 🚀 Features
✅ Add, edit, and delete tasks in real-time  
✅ PostgreSQL database for persistent storage  
✅ REST API with Express.js for backend communication  
✅ React.js frontend with Bootstrap for UI styling  
✅ Fully responsive design  

---

## 🛠 Tech Stack
- **Frontend:** React.js, Bootstrap
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **Styling:** Bootstrap

---

## 📂 Project Structure
```
📂 perntodo-app
 ├── 📁 client        # React Frontend
 │   ├── 📁 src
 │   │   ├── 📁 components  # UI Components
 │   │   │   ├── AddTodo.js
 │   │   │   ├── ListTodos.js
 │   │   │   ├── EditTodo.js
 │   │   ├── App.js
 │   │   ├── index.js
 │   ├── package.json
 │   ├── README.md
 ├── 📁 server        # Node.js Backend
 │   ├── server.js    # Express API
 │   ├── db.js        # Database connection
 │   ├── package.json
 ├── database.sql     # SQL Schema
 ├── README.md        # Project Documentation
```

---

## ⚙️ Setup & Installation
### 🔧 Prerequisites
Make sure you have the following installed:
- Node.js
- PostgreSQL
- npm or yarn

### 📦 Backend Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/perntodo-app.git
   cd perntodo-app/server
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up PostgreSQL:
   - Open PostgreSQL and create a database:
     ```sql
     CREATE DATABASE perntodo;
     ```
   - Run the provided SQL script:
     ```sql
     CREATE TABLE todo (
         todo_id SERIAL PRIMARY KEY,
         description VARCHAR(255)
     );
     ```
4. Update **db.js** with your PostgreSQL credentials.
5. Start the backend server:
   ```bash
   node server.js
   ```

### 🎨 Frontend Setup
1. Navigate to the frontend directory:
   ```bash
   cd ../client
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the frontend:
   ```bash
   npm start
   ```
4. Open **http://localhost:3000** in your browser.

---

## 📌 API Endpoints
| Method | Endpoint         | Description          |
|--------|----------------|----------------------|
| POST   | /todos         | Add a new todo       |
| GET    | /todos         | Get all todos        |
| GET    | /todos/:id     | Get a single todo    |
| PUT    | /todos/:id     | Update a todo        |
| DELETE | /todos/:id     | Delete a todo        |

---ed under the **MIT License**.

---

## 🌟 Acknowledgments
Special thanks to [Lovjeet Singh](https://github.com/LovjeetSingh) for creating this amazing project!

