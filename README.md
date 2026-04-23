# 💬 Real-Time Chatting Application

A full-stack real-time chatting application built using the **MERN stack** with **Socket.io** for instant communication. This app allows users to send messages, share images, and see online/offline status in real time.

---

## 🚀 Features

* 🔐 User Authentication (Login / Signup)
* 💬 Real-time messaging using Socket.io
* 🟢 Online / Offline user status
* 🖼️ Image sharing in chat
* 📩 Message history (stored in database)
* 👀 Seen / Delivered status (optional)
* 📱 Responsive UI (works on all devices)

---

## 🛠️ Tech Stack

### Frontend

* React.js
* Tailwind CSS
* Axios
* Context API

### Backend

* Node.js
* Express.js
* MongoDB (Mongoose)
* Socket.io

### Deployment

* Frontend: Vercel
* Backend: Render / Railway
* Database: MongoDB Atlas

---

## 📁 Folder Structure

```
Chatting-Application/
│
├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── context/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── middleware/
│   ├── models/
│   └── server.js
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/your-username/Chatting-Application.git
cd Chatting-Application
```

---

### 2️⃣ Setup Backend

```
cd backend
npm install
```

Create a `.env` file:

```
PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key
```

Run backend:

```
npm run dev
```

---

### 3️⃣ Setup Frontend

```
cd frontend
npm install
```

Create `.env` file:

```
VITE_BACKEND_URL=http://localhost:5000
```

Run frontend:

```
npm run dev
```

---

## 🌐 API Endpoints

### Auth

* `POST /api/auth/login`
* `POST /api/auth/signup`

### Messages

* `GET /api/messages/:id`
* `POST /api/messages/send/:id`
* `PUT /api/messages/mark/:id`

---

## 🔌 Socket Events

| Event            | Description                  |
| ---------------- | ---------------------------- |
| `sendMessage`    | Send message to another user |
| `newMessage`     | Receive new message          |
| `getOnlineUsers` | Get online users list        |
| `typing`         | Show typing indicator        |

---

## 📸 Screenshots

(Add screenshots here for better presentation)

---

## 🚀 Deployment

### Frontend (Vercel)

```
vercel
```

### Backend (Render)

* Connect GitHub repo
* Add environment variables
* Deploy service

---

## ⚠️ Known Issues

* Socket.io may not work properly on Vercel (use Render/Railway)
* Case-sensitive file issues on deployment (Linux)

---

## 📈 Future Enhancements

* ✔ Voice messages
* ✔ Group chat
* ✔ Video calling
* ✔ Push notifications
* ✔ Dark mode
* ✔ Right tick Marks

---

## 🤝 Contributing

Contributions are welcome!
Feel free to fork this repo and submit a pull request.

---

## 👨‍💻 Author

**Shivpratap Rajawat**

* GitHub: https://github.com/rajawatshivpratap46
* LinkedIn: (Add your LinkedIn here)

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---

