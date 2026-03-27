# 💌 Unsent Letters – Emotional Release Platform

## 🧠 Overview

**Unsent Letters** is a web-based emotional wellness platform designed to help women express feelings they are unable to share openly.
The application allows users to write private letters to anyone (including themselves) without the pressure of sending them.

This platform focuses on **emotional release and mental well-being**, offering a safe and personal space for self-expression.

---

## 🎯 Objective

To provide a secure and judgment-free environment where users can:

* Express suppressed emotions
* Reflect on their thoughts
* Experience emotional relief through writing

---

## ✨ Key Features

### ✍️ Write Letters

* Users can write letters addressed to anyone (self, family, past experiences, etc.)
* No sending mechanism — purely expressive writing

### 🔒 Private Storage

* Letters are securely stored in the database
* Only the logged-in user can access their letters

### 😊 Mood Tracking

* Users select mood **before and after writing**
* Helps understand emotional impact of expression

### 🔥 Burn Letter Feature

* Users can “burn” a letter (delete permanently)
* Includes a visual animation symbolizing emotional release

---

## 💡 Unique Value

Unlike traditional mental health apps that analyze or diagnose,
**Unsent Letters focuses purely on emotional expression and healing.**

* No stress detection
* No AI judgment
* Just a safe space to release emotions

---

## 🛠️ Tech Stack

### Frontend

* HTML
* CSS
* Bootstrap
* JavaScript

### Backend

* PHP

### Database

* MySQL

---

## 🏗️ System Architecture

```
User → Login/Register
      ↓
Write Letter → Store in Database
      ↓
View Letters → Private Dashboard
      ↓
Burn Letter → Delete from Database
```

---

## 🗃️ Database Design

### Table: users

| Field    | Type     |
| -------- | -------- |
| id       | INT (PK) |
| name     | VARCHAR  |
| email    | VARCHAR  |
| password | VARCHAR  |

---

### Table: letters

| Field       | Type      |
| ----------- | --------- |
| id          | INT (PK)  |
| user_id     | INT (FK)  |
| content     | TEXT      |
| mood_before | VARCHAR   |
| mood_after  | VARCHAR   |
| created_at  | TIMESTAMP |

---

## ⚙️ Core Functionalities

### 1. User Authentication

* Secure login and registration system

### 2. Letter Management

* Create, view, and delete letters

### 3. Mood Recording

* Capture emotional state before and after writing

### 4. Burn Mechanism

* Permanently delete letters with animation

---

## 🚀 How to Run the Project

### 🔧 Requirements

* XAMPP / WAMP / LAMP
* PHP 7+
* MySQL

---

### 📥 Setup Steps

1. Clone the repository:

```
git clone https://github.com/your-username/unsent-letters.git
```

2. Move project folder to:

```
htdocs/
```

3. Start:

* Apache
* MySQL

4. Import database:

* Open phpMyAdmin
* Create database: `unsent_letters`
* Import provided `.sql` file

5. Run in browser:

```
http://localhost/unsent-letters
```

---

## 🎨 Future Enhancements

* 🌙 Dark mode UI
* 📊 Mood analytics dashboard
* 🔐 End-to-end encryption
* 📱 Mobile responsiveness improvements
* 🎙️ Voice-to-text letter writing

---

## 🎤 Use Case

This platform is especially helpful for:

* Women dealing with emotional stress
* Individuals who struggle to express feelings
* Anyone seeking a private emotional outlet

---

## 🤝 Contribution

Contributions are welcome!
Feel free to fork this repository and submit pull requests.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 💙 Final Note

*"Sometimes, the words we never send are the ones we most need to write."*
