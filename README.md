# EduBot – AI-Powered Academic Assistant

EduBot is a 24/7 academic assistant built using **Google Gemini API**, **FastAPI**, and a responsive **UI** that supports both light and dark modes. It is designed to help students quickly access information related to exams, curriculum, fees, hostel details, placement data, institutional processes, and more.

---

## 🚀 Features

* **24/7 conversational assistant** for academic queries
* **Gemini API integration** for intelligent responses
* **FastAPI backend** for fast and scalable performance
* **Quick question shortcuts** (Admissions, NAAC, Hostel, Facilities, Placements)
* **Light/Dark theme toggle**
* **Clean, modern UI with chat interface**
* **Database-driven responses with fallback** to admin contacts

---

## 📸 UI Preview

## 🌤️ Light Mode
![Light Mode UI](assets/light_mode.png)

## 🌙 Dark Mode
![Dark Mode UI](assets/dark_mode.png)


---

## 🛠️ Tech Stack

* **Frontend:** HTML, CSS, JavaScript
* **Backend:** FastAPI
* **AI Model:** Google Gemini API
* **Database:** SQL / JSON dataset (configurable)
* **Hosting:** Any server supporting Python + FastAPI

---

## 📂 Project Structure

```
edubot/
│── backend/
│   ├── main.py
│   ├── routes/
│   ├── models/
│   └── services/
│
│── frontend/
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
│── assets/
│   ├── light_mode.jpg
│   └── dark_mode.jpg
│
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
git clone https://github.com/Arrk1821/edubot.git
cd edubot
```

### 2️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Add Your Gemini API Key

Create a `.env` file:

```
GEMINI_API_KEY=your_api_key_here
```

### 4️⃣ Run the FastAPI Server

```
uvicorn backend.main:app --reload
```

### 5️⃣ Open the Frontend

Open the `index.html` file in your browser.

---

## 💡 How It Works

1. User sends a message through the chat UI.
2. FastAPI receives the query and processes it.
3. If the answer exists in the database, it returns instantly.
4. If not, Gemini API generates a response.
5. The UI displays output in a chat bubble format.

---

## 📬 Contact

For improvements, issues, or suggestions, feel free to open a GitHub issue or contact the maintainer.

---

⭐ **If you like this project, don't forget to star the repo!**

