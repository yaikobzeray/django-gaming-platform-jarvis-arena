# 🎮 Jarvis Arena - Gaming Platform

Explore a world of games with the **Jarvis Arena** platform. This project showcases the capabilities of **Django** in social gaming, featuring seamless Google OAuth login and a rich, interactive gaming lobby.

## 🚀 Top Features
- **Social Login:** Secure and fastauthentication with Google OAuth (via django-allauth).
- **Gaming Lobby:** A smooth and interactive hub for exploring games.
- **Multiple Mini-Games:** Built-in browser-based games ready to play.
- **Leaderboards:** Track high scores and compete with other users.
- **Modern UI:** Designed with game lovers in mind for a true immersive feel.
- **Real-Time Interactive Elements:** Showing off modern web mechanics.

## 🛠️ Stack & Technologies
- **Main Framework:** Python, Django
- **Auth Integration:** django-allauth (Google OAuth setup)
- **Frontend Logic:** HTML5, CSS3, JavaScript (Game engines)
- **API Connectivity:** Requests, Django Signals

## ⚙️ Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yaikobzeray/django-gaming-platform-jarvis-arena.git
   cd django-gaming-platform-jarvis-arena
   ```

2. **Set up a virtual environment:**
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install the required packages:**
   ```bash
   pip install django django-allauth requests
   ```

4. **Secret Keys:** Create a `.env` (or configure Django settings) with your Google OAuth credentials.

5. **Run DB Migrations:**
   ```bash
   python manage.py migrate
   ```

6. **Play Now:**
   ```bash
   python manage.py runserver
   ```

Visit `http://127.0.0.1:8004` to enter the arena!

## 🕹️ Available Games
- **Shooter Games**
- **Action Games**
- **Strategy Minis**

## 🤝 Community
Contributions are welcome! Submit a PR or open an issue.

## 📄 License
This project is licensed under the MIT License.
