# 🎉 Event Management Web App

A simple web-based application to manage and display events. Users can view events, and admins can add/manage them using a local database.

---

## 📌 Features

* 📅 View upcoming events
* ➕ Add new events
* 🗂️ Categorize events (Tech, Cultural, etc.)
* 💾 SQLite database integration
* 🌐 Simple web interface

---

## 🛠️ Tech Stack

* Python
* Flask
* SQLite
* HTML / CSS

---

## 📂 Project Structure

```
project-folder/
│── app.py              # Main Flask application
│── database.db         # SQLite database
│── templates/          # HTML files
│── static/             # CSS / JS files
│── README.md           # Project documentation
```

---

## 🚀 How to Run the Project (Step-by-Step)

### 1️⃣ Clone the Repository

```bash
git clone <your-repo-link>
cd <your-repo-folder>
```

---

### 2️⃣ Install Dependencies

Make sure Python is installed, then run:

```bash
pip install flask
```

---

### 3️⃣ Setup Database

Run your database script (if not already created):

```bash
python app.py
```

This will automatically create `database.db` if your code includes setup.

---

### 4️⃣ Run the Application

```bash
python app.py
```

---

### 5️⃣ Open in Browser

Go to:

```
http://127.0.0.1:5000/
```

---

## 🧪 Sample Data

The app comes with sample events like:

* Hackathon Day 1
* Coding Contest
* Workshop

---

## ⚠️ Troubleshooting

### ❌ 'python' not recognized

* Install Python and add it to PATH

### ❌ Port already in use

* Change port in `app.py`:

```python
app.run(port=5001)
```

---

## 📌 Notes

* This project runs **locally only**
* No cloud deployment is required (used only for presentation/demo)

---

## 👨‍💻 Author

* Parth Patel

---

## 📄 License

This project is for educational purposes.
