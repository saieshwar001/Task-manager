# Task Manager Kanban App

A full-stack Kanban board application inspired by Wekan, built with modern web technologies to manage tasks and projects efficiently.

This is my personal project, showcasing **React, Node.js, Express, MongoDB**, and real-time updates.

---

## 🚀 Features

* Create multiple **boards**, **lists**, and **cards**
* **Drag and drop** cards between lists
* **User authentication** (signup/login)
* Assign **tasks to users**
* Real-time updates with **WebSockets**
* Search and filter tasks
* Responsive design for desktop and mobile

---

## 🛠️ Tech Stack

* **Frontend:** React, Redux, Tailwind CSS
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **Realtime:** Socket.IO
* **Deployment:** Docker (optional), Heroku/Vercel

---

## 💻 Installation

1. Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/Task-manager.git
cd Task-manager
```

2. Install dependencies:

```bash
# Backend
npm install

# Frontend (in client folder)
cd client
npm install
```

3. Create a `.env` file in the root:

```text
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000
```

4. Start development server:

```bash
# Backend
npm run dev

# Frontend (in client folder)
npm start
```

5. Open `http://localhost:3000` in your browser

---

## 📦 Deployment

You can deploy this app using **Docker**, **Heroku**, or **Vercel** for production.
A simple Docker setup is included in `docker-compose.yml`.

---

## 📝 Future Improvements

* Add **notifications** for task updates
* Support **team collaboration**
* Export/Import boards
* Analytics dashboard for tasks

---

## 📂 Project Structure

```
/client      # React frontend
/server      # Express backend
/models      # MongoDB schemas
/routes      # API endpoints
/controllers # Backend logic
```

---

## 📌 Contribution

This is a personal project. Contributions are welcome via **pull requests** if you want to add features.

---

## 🔗 Links

* Live Demo: [Coming soon]
* Portfolio: [Your Portfolio URL]

---

## 📄 License

This project is released under the **MIT License**.
