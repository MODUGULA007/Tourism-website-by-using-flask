# 🧳 Tourism Website using Flask

A responsive tourism web application built with **Flask (Python)** and **Bootstrap**, allowing users to view travel destinations, submit details, and interact with a dynamic interface. This project includes data storage with CSV and optionally SQLite.

---

## 🚀 Features

- 🏞️ View tourism destinations
- 📥 Collect user data via forms
- ⏪⏩ History replay of calculations
- 📊 Store and load data from CSV/Database
- 🎨 Responsive UI with Bootstrap
- 🧠 Intelligent keyboard and mouse input support

---

## 💻 Technologies Used

| Layer       | Technology                    |
|-------------|-------------------------------|
| Backend     | Python 3, Flask               |
| Frontend    | HTML5, CSS3, JavaScript       |
| UI Styling  | Bootstrap 5, jQuery           |
| Database    | CSV, (Optional: SQLite)       |

---

## 📂 Folder Structure

```plaintext
├── app1.py               # Main Flask app
├── templates/            # HTML templates (Flask views)
├── static/               # CSS, JS, images
├── user_details.csv      # CSV user storage
├── requirements.txt      # Dependencies
└── README.md             # This file
```

---

## 🧪 How to Run

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/tourism-website.git
   cd tourism-website
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask app**
   ```bash
   python app1.py
   ```

4. Open browser at: `http://127.0.0.1:5000`

---

## 📦 Dependencies (`requirements.txt`)

```txt
Flask==2.3.2
pandas==2.1.3
```

> You can add more if needed.

---

## 🔒 .gitignore (Optional but Recommended)

```gitignore
__pycache__/
*.pyc
*.db
*.zip
.env
```

---

## 📜 License

MIT License - Use it freely in personal or commercial projects.
