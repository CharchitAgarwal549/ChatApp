# 💬 QuickCon Chat App

QuickCon is a real-time chat application that enables users to create accounts, connect with others, and exchange messages instantly. It offers a seamless chatting experience with secure authentication and a responsive design.

🔗 **Live Demo:** [QuickCon](https://chatapp1-4d99.onrender.com/)  
📂 **GitHub Repo:** [ChatApp Repository](https://github.com/CharchitAgarwal549/ChatApp)

---

## 🛠 Tech Stack
- **Frontend:** React.js, Tailwind CSS  
- **Backend:** Node.js, Express.js, Socket.IO  
- **Database:** MongoDB  
- **Other Tools:** JWT Authentication, bcrypt.js, Cloudinary (for profile images), Render (Deployment)

---

## ⚡ Features
- 🔐 Secure **user authentication & authorization** with JWT.  
- 💬 **Real-time messaging** powered by **Socket.IO**.  
- 👤 Profile management with Cloudinary image uploads.  
- 📱 Fully responsive UI (mobile & desktop friendly).  
- 📡 Online/offline user status tracking.  
- 🕒 Chat history stored in MongoDB.  

---

## 📂 Project Structure
ChatApp/
│-- backend/ # Node.js + Express backend
│ │-- src/
│ │ │-- controllers/ # Business logic for routes
│ │ │-- lib/ # Helper functions/utilities
│ │ │-- middleware/ # Authentication & error handling
│ │ │-- models/ # MongoDB schemas (User, Messages, Chats)
│ │ │-- routes/ # API routes
│ │ │-- seeds/ # Initial database seeding
│ │ └-- index.js # App entry point
│ │
│ │-- package.json
│ │-- package-lock.json
│
│-- frontend/ # React frontend
│ │-- package.json
│
│-- .gitignore
│-- package.json # Root config

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/CharchitAgarwal549/ChatApp.git
cd ChatApp
````

### 2. Setup Backend

```bash
cd backend
npm install
node src/index.js
```

### 3. Setup Frontend

```bash
cd frontend
npm install
npm run dev
```

### 4. Environment Variables

Create a `.env` file inside the `server/` folder with the following keys:

```
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

# Cloudinary (for storing profile images)
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

---

## 🎯 Future Improvements

* ✅ Group chats and broadcasting.
* ✅ Typing indicators and read receipts.
* ✅ Push notifications for new messages.
* ✅ End-to-end encryption for better security.

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!
Feel free to fork this repo and submit a pull request.

---

## 📜 License

This project is licensed under the MIT License.

---

### 👨‍💻 Author

**Charchit Agarwal**
🔗 [GitHub](https://github.com/CharchitAgarwal549)
🔗 [LinkedIn](https://www.linkedin.com/in/charchit-agarwal-/)

```
