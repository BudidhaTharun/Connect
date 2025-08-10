# 💬 MessageKaro – Your Real-Time Chatting Platform

**MessageKaro** is a full-stack, modern chat application enabling seamless, real-time conversations, group discussions, and media sharing. Powered by the MERN stack (MongoDB, Express.js, React.js, Node.js), real-time messaging via Socket.IO, and media storage using Cloudinary, MessageKaro delivers a fast, secure, and user-friendly chatting experience.

---

## 🚀 Why MessageKaro?

- **Instant Messaging:** Send and receive messages in real time.
- **Group & Private Chats:** Talk one-on-one or create vibrant group conversations.
- **Media Sharing:** Effortlessly share images and files, securely stored on Cloudinary.
- **Simple, Modern UI:** Responsive, intuitive interface for all devices.
- **Secure Authentication:** Keep your chats safe with protected sign up and login.
- **Message History:** Access previous conversations at any time.

---

## 🛠️ Tech Stack

| Layer        | Technology                                                              |
|--------------|-------------------------------------------------------------------------|
| Frontend     | React.js                                                                |
| Backend      | Node.js, Express.js                                                     |
| Database     | MongoDB                                                                 |
| Real-Time    | Socket.IO                                                               |
| Media Upload | Cloudinary                                                              |

---

## 🗺️ How it Works

1. **Sign up and log in** to your secure account.
2. **Create or join chats**—either one-to-one or group.
3. **Send messages** instantly with real-time updates thanks to Socket.IO.
4. **Share images and files**—they're uploaded and stored on Cloudinary.
5. **Browse your chat history** any time.

---

## 🏁 Getting Started

### Prerequisites

- Node.js & npm
- MongoDB (local or Atlas)
- Cloudinary account (for media uploads)

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/messagekaro.git
cd messagekaro
```

### 2. Install Dependencies

- Backend:
  ```bash
  cd backend
  npm install
  ```
- Frontend:
  ```bash
  cd ../frontend
  npm install
  ```

### 3. Set Up Environment Variables

Create `.env` files in both `backend` and `frontend` with your MongoDB URI, Cloudinary credentials, and other secrets.

### 4. Run the App

- Backend:
  ```bash
  npm start
  ```
- Frontend (in a new terminal):
  ```bash
  npm start
  ```

---

## 📚 API Overview

### Authentication

- `POST /api/auth/login` – Login
- `POST /api/auth/register` – Register

### Chats

- `GET /api/chats` – List user's chats
- `POST /api/chats` – Create new chat/group

### Messages

- `GET /api/messages/:chatId` – Fetch messages from a chat
- `POST /api/messages` – Send a message

---

## 🙌 Contributing

We 💙 contributors! To get started:

1. **Fork** this repo and clone your fork.
2. Create a **feature branch** (`git checkout -b my-feature`).
3. Make your changes.
4. Push and open a **pull request**!

---

## 🛠️ Troubleshooting

- **MongoDB Connection Issues:**  
  - Check your `.env` for a valid `MONGO_URI`.
  - Ensure MongoDB is running locally or your Atlas URI is correct.

- **Cloudinary Uploads Not Working:**  
  - Double-check your Cloudinary keys in `.env`.

- **Real-Time Messaging Not Working:**  
  - Ensure the backend server is running and Socket.IO is correctly configured.
  - Check client-server connection URLs.

---

## ❓ FAQ

**Q:** Can I use MessageKaro for group chats?  
**A:** Yes! Create group chats and add multiple members.

**Q:** Is my data secure?  
**A:** Passwords are hashed, and only authorized users can access messages.

**Q:** Can I share files or images?  
**A:** Absolutely! Media is uploaded to Cloudinary and linked in your chats.

---

## 📄 .env Sample (Backend)

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

---

## 🤝 Credits

- **Made by:** [@BudidhaTharun](https://github.com/BudidhaTharun) & MessageKaro contributors

---

<p align="center">
  <b>Built for seamless, real-time connection.<br/>
  Made with ❤️ – Chat smarter, together!
  </b>
</p>
