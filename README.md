# 🎮 Gaming E-Commerce Platform

## 🌟 Project Overview
Welcome to the **Gaming E-Commerce Platform**! This application provides a robust system for users to browse, purchase, and manage games, along with integrated chat and admin functionalities. The platform is built using Node.js, Express, MongoDB, and EJS, making it highly scalable and efficient.

---

## 🚀 Features

### 🔑 User Features
- **Authentication:** Secure login, registration, and password recovery.
- **Game Browsing:** Search, filter by genres, categories, and view detailed game pages.
- **Cart Management:** Add, view, and remove games in the cart.
- **Purchase & Downloads:** Secure game purchases and instant downloads.
- **Chat System:** Real-time chat between users.

### 🛠️ Admin/Manager Features
- **Admin Dashboard:** View login and registration details.
- **Account Management:** Update passwords, delete accounts, and assign roles.
- **Analytics:** Retrieve statistics on user activity.

### 📦 Backend Features
- **Dynamic Routing:** Modular routes for scalability and maintainability.
- **Database Management:** MongoDB integration for storing user, game, and chat data.
- **Real-Time Messaging:** Chat feature with user contact history retrieval.
- **Efficient JSON Handling:** Automated population of game database from JSON files.

---

## 🛠️ Tech Stack

### Backend:
- **Node.js** with **Express.js**
- **MongoDB** for data storage
- **Mongoose** for database schema modeling


### Frontend:
- **HTML5, CSS3, JavaScript**
- **EJS** for server-side rendering

---

## 📁 Project Structure
```plaintext

├── app.js
├── controllers
│   ├── admin_manager.js
│   ├── cart.js
│   ├── chat.js
│   ├── def.js
│   ├── gamepage.js
│   ├── home.js
│   ├── login.js
│   ├── payment.js
│   ├── register.js
│   ├── register2.js
│   └── user.js
├── folderstr.js
├── models
│   ├── accountschema.js
│   ├── connect.js
│   ├── games.json
│   ├── gameschema.js
│   └── messageschema.js
├── package-lock.json
├── package.json
├── public
│   ├── about.html
│   ├── admin.ejs
│   ├── admin_manager.js
│   ├── cart.html
│   ├── cartpayment.html
│   ├── chat.html
│   ├── css
│   ├── faq.ejs
│   ├── faq.html
│   ├── fonts
│   ├── footer.html
│   ├── fpassword.html
│   ├── game-page.html
│   ├── genre.html
│   ├── header.html
│   ├── header1.html
│   ├── home.html
│   ├── home.js
│   ├── images
│   ├── manager.ejs
│   ├── manager.js
│   ├── navigationbar.html
│   ├── news.html
│   ├── news.js
│   ├── payment.html
│   ├── register.html
│   ├── register2.html
│   ├── search.html
│   ├── t.html
│   ├── userprofile.html
│   ├── userprofile.js
│   ├── user_chat.html
│   ├── v3.js
│   ├── verify.js
│   └── verify2.js
└── routes
|   └── router.js
├── .env
├── .gitignore
```
## 🔗 API Endpoints

### User Routes
- `GET /home` - Home page
- `GET /login` - Login page
- `POST /login` - User login
- `GET /register` - Registration page
- `POST /register` - User registration
- `GET /user` - Fetch user data

### Game Routes
- `GET /games` - Browse games
- `GET /game-page` - View game details
- `POST /getGame` - Fetch specific game data

### Admin Routes
- `GET /admin` - Admin dashboard
- `POST /admin/updatepassword` - Update admin password
- `POST /admin/delAcc` - Delete user account
- `POST /admin/updaterole` - Update user roles

### Chat Routes
- `GET /chat` - Individual chat page
- `POST /send` - Send a message
- `GET /messages/:recipientId` - Fetch chat messages

### Payment Routes
- `POST /paygame` - Game purchase
- `POST /downloadgame` - Game download

```
## ⚙️ Installation
```
1. Clone the repository:
   ```bash
    git clone https://github.com/SagarMantina/P2P-DIGITIAL-GAMING-MARKET-PLACE-.git
   ```
   
2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up the `.env` file:
   ```env
   MONGO_URI=your_mongodb_connection_string
   PORT=3000
   ```

4. Start the server:
   ```bash
   npm start
   ```

5. Access the platform at `http://localhost:3000`

---

## 🛡️ Security Measures
- **Cookie-based authentication** for session management.
- **Environment variables** for sensitive data.
- **Data validation** to prevent SQL/NoSQL injection.

---

## 🤝 Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository
2. Create a new branch (`git checkout -b feature/YourFeatureName`)
3. Commit your changes (`git commit -m 'Add your message here'`)
4. Push to the branch (`git push origin feature/YourFeatureName`)
5. Open a Pull Request

---

## 📝 License
This project is licensed under the [MIT License](LICENSE).

---

## 📧 Contact
For any inquiries, feel free to reach out:
- Email: sagarmantina11@gmail.com
- GitHub: https://github.com/SagarMantina/

---


