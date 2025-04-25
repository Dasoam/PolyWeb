
# PolyWeb

A simple Python web application built as a **first-semester college project** to help students find romantic partners on campus.

---

## 💖 Project Purpose

PolyWeb was designed to make it easier for college students to connect and find love on campus. The app allows users to browse profiles, express interest, and rate potential matches, helping students form meaningful romantic connections in a safe and friendly environment.

---

## 🏗️ Project Structure

```
PolyWeb/
├── static/               # Static assets (CSS, JS, images)
├── templates/            # HTML templates for web pages
│   ├── index.html
│   ├── data.html
│   ├── data1.html
│   └── rating page.html
├── fk.py                 # Main Python application file
├── .gitignore
├── LICENSE
└── README.md
```

---

## ✨ Features

- **Student Profiles:** Browse a list of students looking for love.
- **Matchmaking:** Find and connect with students based on shared interests or preferences.
- **Ratings & Feedback:** Use the rating page to express interest or rate potential matches.
- **Dynamic Web Pages:** Multiple templates for different parts of the app.
- **Static File Management:** Organized CSS, JavaScript, and image assets.

---

## 🚀 Getting Started

### Prerequisites

- Python 3

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Dasoam/PolyWeb.git
   cd PolyWeb
   ```

2. **Install Dependencies:**
   - If using Flask (most likely), install it:
     ```bash
     pip install flask
     ```

3. **Run the Application:**
   ```bash
   python fk.py
   ```

4. **Access the App:**
   - Open your browser and go to `http://localhost:5000` (or the port specified in `fk.py`).

---

## 🖼️ Templates Overview

| File              | Purpose                                         |
|-------------------|-------------------------------------------------|
| index.html        | Main landing page and introduction              |
| data.html         | Student profiles and partner search             |
| data1.html        | Alternative view for browsing matches           |
| rating page.html  | Express interest or rate potential matches      |

---

## 📝 Usage

- **Home:** Visit the root URL for an introduction and navigation.
- **Find Love:** Use the data pages to browse and connect with other students.
- **Express Interest:** Visit the rating page to rate or show interest in matches.

---

## 📄 License

This project is licensed under the MIT License.
