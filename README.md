# Flask-Pastebin

**Flask-Pastebin** is a simple demonstration web application built with Flask.  
It implements a basic pastebin service while showcasing integration with several Flask extensions and real-time push functionality.

---

## Features

- **Facebook Connect** – User authentication via Facebook  
- **Realtime Push Notifications** – Uses Juggernaut for live updates  
- **Pagination** – Demonstrates basic pagination for paste entries  

---

## Technologies Used

- [Flask](https://flask.palletsprojects.com/) – Web framework  
- [Flask-OAuth](https://pythonhosted.org/Flask-OAuth/) – OAuth integration  
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/) – ORM for database access  
- [Flask-Script](https://flask-script.readthedocs.io/) – Command-line utilities  
- [Juggernaut](https://github.com/maccman/juggernaut) – Real-time push server  

---

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/flask-pastebin.git
   cd flask-pastebin
   ```

2. **Create and activate a virtual environment**
   ```bash
   python3 -m venv venv
   source venv/bin/activate   # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **Set up the database**
   ```bash
   flask db upgrade
   ```

5. **Run the application**
   ```bash
   flask run
   ```
   The app will be available at: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## Usage

Once running, you can:
- Log in with Facebook  
- Create new pastes  
- Receive realtime updates via Juggernaut  
- Browse pastes with pagination  

---

## License

This project is intended for educational and demonstration purposes only.
