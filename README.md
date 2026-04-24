# 🤖⚽ AI vs Player Guess Game

An interactive web-based AI game where **you and the AI compete** to guess a football player from **Barcelona or Real Madrid**.

---

## 🎮 Game Idea
- 🤖 AI asks you questions → you answer YES / NO  
- 🧑 You ask the AI questions → AI answers YES / NO  
- Both try to **figure out the hidden player**

👉 First to guess correctly wins!

---

## 🧠 AI Concept

This project implements a **Model-Based AI Agent**:

- Uses player data (JSON)
- Filters possibilities based on answers
- Chooses the **best question** using decision logic (balanced split)

---

## 🏗️ Project Structure


ai_guess_game/
│
├── app.py
├── players.json
├── questions.json
│
├── templates/
│ └── index.html
│
├── static/
│ ├── style.css
│ ├── script.js
│ └── images/
│ └── myface.jpeg


---

## ⚙️ Technology Stack

- **Backend:** Python + Flask  
- **Frontend:** HTML, CSS, JavaScript  
- **Database:** JSON (can be upgraded to SQLite)  
- **Concepts:**  
  - AI Agents  
  - Decision Making  
  - Data Structures  

---


## 🚀 How to Run

1. Install Flask:

pip install flask


2. Run the app:

python app.py


3. Open browser:

http://127.0.0.1:5000


---

## Team Members:
- Mohamed Karam Mohamed
- Mohamed Farid Mansour
- Mohamed Farid El-sherbiny

