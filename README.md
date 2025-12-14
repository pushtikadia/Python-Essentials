# 🐍 Python Essentials

**Python Essentials** is a comprehensive learning repository designed to take you from writing your first line of code to building database-backed applications. It documents a structured journey through core Python concepts, logic building, and real-world implementation.

## 📂 Repository Structure

The code is organized into progressive modules, making it easy to navigate through different concepts:

### 🔹 Core Concepts
* **01 Basics:** Syntax, comments, and running programs.
* **02 Conditionals:** Decision making with `if`, `elif`, `else`.
* **03 Loops:** Iteration using `for` and `while` loops.
* **04 Functions:** Reusable code blocks, arguments, and return values.
* **05 Scopes:** Understanding local vs. global scope.
* **06 OOP:** Object-Oriented Programming principles.
* **07 Decorators:** Enhancing functions with decorators.

### 🚀 Practical Projects & Integrations
* **08 Python Project (File Handling):** A CLI-based **YouTube Manager** app that allows users to CRUD (Create, Read, Update, Delete) video details using a local JSON file (`youtube.txt`).
* **09 Database (SQLite3):** An evolution of the YouTube Manager that persists data using Python's built-in `sqlite3` module.
* **10 Handling APIs:** Scripts demonstrating how to interact with external APIs (e.g., fetching random user data).
* **11 YouTube Manager (MongoDB):** An advanced version of the manager app connecting to a cloud-based **MongoDB** cluster using `pymongo`.

---

## 🛠️ Projects Showcase

### 📺 YouTube Manager App (Versions 1-3)
This repository features three iterations of a "YouTube Video Manager" to demonstrate data persistence evolution:

1.  **File-Based:** Uses `json` module to save data to a text file.
2.  **SQL-Based:** Implements a relational database schema (`videos` table) with `sqlite3`.
3.  **NoSQL-Based:** Connects to MongoDB Atlas to manage documents in a `ytmanager` database.

---

## 🚀 Getting Started

### Prerequisites
* Python 3.x installed.
* `pymongo` installed (for Module 11).

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/pushtikadia/Python-Essentials.git](https://github.com/pushtikadia/Python-Essentials.git)
    ```
2.  **Navigate to the directory:**
    ```bash
    cd Python-Essentials
    ```
3.  **Install dependencies (for MongoDB project):**
    ```bash
    pip install pymongo
    ```
4.  **Run a script:**
    ```bash
    python "08_python_project/youtube_manager.py"
    ```

---

## ⚙️ Technologies Used

* **Language:** Python 3
* **Databases:** SQLite3, MongoDB (NoSQL)
* **Libraries:** `json`, `sqlite3`, `pymongo`, `requests` (for APIs)

---
  *Created by [Pushti Kadia](https://github.com/pushtikadia)*
