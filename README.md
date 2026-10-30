# PyLearn Hub 🐍

An interactive Python learning website for students — write code, play games, take quizzes, and level up!

## Features

- **Live Editor** — Type Python and see output update in real time
- **Script Mode** — Write your full program, then run it
- **Quiz Levels** — 30 levels of quizzes (easy → hard) with progress tracking
- **10 Mini Games** — Snake, Tic Tac Toe, Memory Match, Typing Test, and more
- **Training** — Structured lessons from basics to advanced
- **User System** — Register, login, track your progress

## Quick Start

```bash
# Clone the repo
git clone https://github.com/YOUR_USERNAME/pylearn-hub.git
cd pylearn-hub

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```

Open **http://localhost:5000** in your browser.

## Tech Stack

- **Backend:** Python, Flask
- **Frontend:** HTML, CSS, JavaScript (no frameworks)
- **Database:** SQLite (built-in, zero config)
- **Auth:** Session-based with password hashing

## Project Structure

```
pylearn-hub/
├── app.py                 # Flask app & all routes
├── requirements.txt       # Python dependencies
├── pylearn.db             # SQLite database (auto-created)
├── .gitignore
├── Procfile               # For Render / Heroku deployment
├── README.md
└── templates/
    ├── base.html          # Shared layout
    ├── index.html         # Home page
    ├── login.html         # Login page
    ├── register.html      # Register page
    ├── editor.html        # Live editor
    ├── script.html        # Script mode
    ├── play.html          # Quiz levels
    ├── games.html         # 10 mini games
    └── training.html      # Lessons
```

## Deployment

### Render (free)
1. Push to GitHub
2. Go to [render.com](https://render.com) → New Web Service
3. Connect your repo
4. Build command: `pip install -r requirements.txt`
5. Start command: `python app.py`

### Vercel
Use the Vercel Python adapter or deploy as a serverless function.

## License

MIT — free to use, modify, and share.
