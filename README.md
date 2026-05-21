# 🏰 EmpireX — March of Empires

<div align="center">

![EmpireX Banner](img1.png)

### ⚔️ A Medieval Fantasy MMO Strategy Game

Build your empire, forge alliances, and conquer the realm in an immersive multiplayer strategy experience.

[![Flask](https://img.shields.io/badge/Flask-3.0.2-black?style=for-the-badge&logo=flask)](https://flask.palletsprojects.com/)
[![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)](https://www.python.org/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13+-336791?style=for-the-badge&logo=postgresql)](https://www.postgresql.org/)
[![Railway](https://img.shields.io/badge/Deployed_on-Railway-0B0D0E?style=for-the-badge&logo=railway)](https://railway.app/)

</div>

---

## 🌐 Live Demo

🔗 **Play Now:**  
https://empirex-sk.onrender.com

---

# ✨ Features

| Feature | Description |
|---------|-------------|
| 🏗️ Empire Building | Construct and upgrade buildings to strengthen your kingdom |
| ⚔️ Strategic Warfare | Command armies in tactical real-time battles |
| 🤝 Alliance System | Form alliances and dominate the realm together |
| 👑 Faction Selection | Choose unique factions with special bonuses |
| 🏆 Tournaments | Participate in seasonal events and competitions |
| 💬 Real-time Chat | Coordinate using Flask-SocketIO |
| 🔐 Secure Authentication | Flask-Login + Bcrypt powered security |

---

# 🖼️ Screenshots

<div align="center">


<img src="img2.png" width="30%">
<img src="img3.png" width="30%">
<img src="img4.png" width="30%">

</div>

---

# 🏆 Gameplay Features

## 🏰 Empire Building

- Construct 15+ unique structures
- Upgrade cities and defenses
- Research powerful technologies
- Manage economy and resources

## ⚔️ Warfare System

- Multiple troop classes
- Formation-based combat
- Siege warfare mechanics
- Special abilities and spells

## 🌍 Multiplayer Experience

- Persistent online world
- Alliance management
- Real-time player chat
- Weekly tournaments and rankings

---

# 🛠️ Tech Stack

## Backend

- **Framework:** Flask 3.0.2
- **Database:** PostgreSQL + SQLAlchemy
- **Authentication:** Flask-Login & Flask-Bcrypt
- **Realtime:** Flask-SocketIO
- **Payments:** PayPal REST SDK
- **Email Service:** Flask-Mail

## Frontend

- HTML5
- CSS3
- JavaScript
- Responsive UI Design

## Deployment

- Railway
- Gunicorn
- Eventlet

---

# 📊 Project Stats

```mermaid
pie
    title Game Achievements
    "Happy Players" : 150
    "Levels Completed" : 75
    "Awards Won" : 28
    "Achievements" : 100
```

---

# 📅 Development Timeline

```mermaid
gantt
    title Development Timeline
    dateFormat YYYY-MM-DD

    section Core Features
    Authentication :done, auth1, 2024-01-01, 14d
    Empire Building :done, emp1, after auth1, 21d
    Combat System :done, comb1, after emp1, 28d

    section Multiplayer
    Alliance System :active, all1, 2024-02-20, 21d
    World Map :wmap1, after all1, 30d
    Tournaments :tour1, after wmap1, 14d
```

---

# ⚙️ Architecture

```mermaid
graph TD
    A[Client] -->|HTTP/WebSocket| B[Flask Server]
    B --> C[PostgreSQL]
    B --> D[Redis Cache]
    C --> E[Player Data]
    C --> F[Game State]
    D --> G[Session Cache]
    D --> H[Leaderboards]
    B --> I[Payment Processing]
    I --> J[PayPal API]
```

---

# 🚀 Installation

## Prerequisites

- Python 3.10+
- PostgreSQL 13+
- Redis

---

## Clone Repository

```bash
git clone https://github.com/itshivam96/EmpireX.git
cd EmpireX
```

---

## Create Virtual Environment

### Linux / macOS

```bash
python -m venv venv
source venv/bin/activate
```

### Windows

```bash
venv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Configure Environment Variables

```bash
cp .env.example .env
```

Edit `.env` with your credentials.

---

## Initialize Database

```bash
flask db upgrade
```

---

## Run Application

```bash
flask run
```

---

# 📁 Project Structure

```bash
EmpireX/
│
├── app/
├── static/
├── templates/
├── migrations/
├── requirements.txt
├── config.py
├── run.py
└── README.md
```

---

# 🔐 Environment Variables

Example `.env`

```env
SECRET_KEY=your_secret_key
DATABASE_URL=postgresql://user:password@localhost/empirex
MAIL_USERNAME=your_email
MAIL_PASSWORD=your_password
PAYPAL_CLIENT_ID=your_paypal_client_id
PAYPAL_SECRET=your_paypal_secret
```

---

# 🌟 Future Plans

- 🗺️ Open World Expansion
- 🐉 Mythical Creatures
- ⚡ PvP Arena Mode
- 🏰 Kingdom Raids
- 📱 Mobile App Version

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the project
2. Create your feature branch
3. Commit changes
4. Push to branch
5. Open a Pull Request

---

# 📜 License

This project is licensed under the MIT License.

---

# 👨‍💻 Developer

### Shivam Kumar
GitHub: https://github.com/itshivam96

---

<div align="center">

## ⭐ Support the Project

If you like this project, give it a ⭐ on GitHub!

</div>
