# 🎓 Student Course Management System (MERN Stack)

A full-stack web application built using the **MERN** (MongoDB, Express, React, Node.js) stack. This system allows an **Admin** to manage students and courses efficiently, including full CRUD operations and user authentication.

---

## 🚀 Features

- 📚 **Course Management** — Add, view, update, delete courses
- 👨‍🎓 **Student Management** — Add, view, update, delete students
- 🔐 **Admin Authentication** — Secure login and signup system (Coming up!)
- 🔄 **Course Enrollment** — Students can be enrolled in multiple courses (Planned)
- 💻 **Responsive Frontend** — Built with React.js & styled-components
- 🌐 **MongoDB Atlas** — Hosted cloud database
- ⚙️ **Backend API** — Built with Express.js and Node.js

---

## 🛠️ Tech Stack

| Layer       | Technology               |
|-------------|---------------------------|
| Frontend    | React.js, styled-components |
| Backend     | Node.js, Express.js       |
| Database    | MongoDB (MongoDB Atlas)   |
| Deployment  | Backend: Render<br>Frontend: GitHub Pages / Vercel (optional) |

---

## 📁 Folder Structure

student-course-management/ │ ├── backend/ # Express server and API │ └── models/ # Mongoose models (Student, Course) │ └── routes/ # API Routes │ └── controllers/ # Logic handlers │ └── server.js │ ├── frontend/ │ └── student-course-management/ │ └── src/ │ └── components/ │ └── pages/ │ └── App.js │ └── README.md 



# Project overview


---

## ✅ How to Run Locally

### 🔧 Prerequisites

- Node.js & npm installed
- MongoDB Atlas URI (or local MongoDB)

---

### 1. Clone the Repository

git clone https://github.com/yourusername/student-course-management.git
cd student-course-management

cd backend
npm install
npm start


Create a .env file inside /backend and add your MongoDB URI:
MONGO_URI=your_mongodb_connection_string


Start the Frontend App
cd frontend/student-course-management
npm install
npm start
App will run at http://localhost:3000.



##🌱 Upcoming Features

 CRUD for students & courses
 Admin login & signup 🔐
 Course enrollment logic
 Filter & search students/courses
 Deployment (fully hosted)

 
🤝 Contribution

This is a Duo college mini-project developed for hands-on MERN stack practice. Contributions, ideas, and suggestions are welcome!

📧 Contact
Nandlal Patil
📫 Email: nandlal.patil@gmail.com

📝 License
This project is open-source and free to use for learning and academic purposes.


---

✅ After pasting this into your `README.md`, save and run:

```bash
git add README.md
git commit -m "📝 Added final README"
git push


