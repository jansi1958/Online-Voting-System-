# 🗳️ Online Voting System

A secure, full-stack web application that allows users to cast their votes electronically. Built with Java on the backend and a clean HTML/CSS frontend, the system ensures a seamless and tamper-proof voting experience.

---

## ✨ Features

- **User Registration & Authentication** — Secure voter login and session management
- **Admin Panel** — Manage elections, add candidates, and monitor live voting progress
- **Voting Mechanism** — Simple, intuitive interface for casting votes
- **Results Display** — Real-time or post-voting display of election results
- **Data Security** — Votes stored securely with tamper-proof database design

---

## 🛠️ Tech Stack

| Layer     | Technology                        |
|-----------|-----------------------------------|
| Frontend  | HTML, CSS                         |
| Backend   | Java (Core logic, Server-side)    |
| Database  | MySQL / SQL-compatible DB         |
| Server    | Apache Tomcat                     |

---

## ⚙️ Prerequisites

Make sure you have the following installed:

- [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/)
- [Apache Tomcat](https://tomcat.apache.org/)
- [MySQL](https://www.mysql.com/) or any SQL-compatible database

---

## 🚀 Getting Started

1. **Clone the repository**
```bash
   git clone https://github.com/Ongkar08/online-voting-system.git
   cd online-voting-system
```

2. **Set up the database**
   - Create a MySQL database
   - Import the provided `.sql` schema file

3. **Configure database connection**
   - Update DB credentials in the connection config file

4. **Deploy on Tomcat**
   - Build the project and deploy the `.war` file to your Tomcat `webapps` folder
   - Start the Tomcat server

5. **Access the app**
   - Open `http://localhost:8080/online-voting-system` in your browser

---

## 👥 Usage

| Role  | Actions |
|-------|---------|
| **Voter** | Register, log in, and cast your vote |
| **Admin** | Log in, manage elections, add candidates, monitor results |

---

## 🔮 Future Enhancements

- [ ] Two-factor authentication (2FA) for enhanced security
- [ ] Blockchain integration for immutable vote integrity
- [ ] Enhanced UI/UX for a better user experience

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
