# DevLog
# DevLog - Your Personal Developer Diary 🧠📓

DevLog is a minimalist, full-stack diary web app crafted especially for developers who want to log their daily learning, reflect on their progress, and automatically build a portfolio that speaks for itself.

---

## 🌟 Why DevLog?
> Great developers aren’t made in a day — they are built *one log at a time*.

DevLog helps you:
- Record daily learning notes (coding, problem-solving, bugs fixed)
- Visualize your growth over time
- Export your journey into a clean public portfolio
- Stay consistent and accountable

Whether you're a complete beginner or aiming for your dream job, DevLog becomes your **habit builder**, **career tracker**, and **self-reflection engine**.

---

## 🔧 Tech Stack

### Frontend
- HTML5, CSS3
- Bootstrap 5
- Icons via Bootstrap Icons

### Backend
- Python 3 + Flask
- SQLite (Zero setup DB)
- Jinja2 Templating

### Auth & Security
- User Registration & Login
- Password Hashing (via werkzeug)
- Flask Session Handling

---

## 📁 File Structure
```
DevLog/
├── app.py
├── static/
│   └── css/
│       └── style.css
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── register.html
│   └── dashboard.html
├── models.py
├── database.db (auto created)
└── README.md
```

---

## 🚀 Getting Started

1. **Clone the repo**
```bash
git clone https://github.com/amar-01/DevLog.git
cd DevLog
```

2. **Install dependencies**
```bash
pip install flask
```

3. **Run the app**
```bash
python app.py
```
Visit `http://127.0.0.1:5000` in your browser.

---

## ✅ Features
- [x] Landing Page with app intro
- [x] User Registration & Login
- [x] Diary Dashboard
- [ ] Add/Edit/Delete Logs *(coming next)*
- [ ] Data Visualization *(optional upgrade)*
- [ ] Exportable Portfolio *(optional upgrade)*

---

## 🧠 How It Works

1. User visits the homepage ➜ clicks **Register** to sign up.
2. Fills a simple form and creates an account securely.
3. Logs in and starts writing daily developer notes.
4. Logs saved to database and shown in dashboard.
5. Future scope: export logs into markdown/HTML portfolios.

---

## 📌 Why This Project Matters
This isn't just a diary. It’s a foundation project that shows:
- You know how to structure a full web app
- You understand authentication & sessions
- You can scale it into a real product (portfolio SaaS, AI auto-tagger, GitHub sync)

Perfect to showcase in interviews or build into a full-fledged dev tool.

---

## 👨‍💻 Made By
**You**, an aspiring developer going from Zero to Hero 🚀

---

## 🏁 Ready to Get Logging?
Track your growth. Build your story. With **DevLog**.

> "What gets measured, gets improved." – Peter Drucker
