# GUI – ToDo App

A desktop To-Do list application built with Java Swing.

## ✨ Features
- Add new tasks with date & time
- Delete tasks
- Mark tasks as completed ([✔])
- Saves tasks to a file so they remain after closing the app
- Loads saved tasks automatically on startup

---

## 📦 Requirements
- Java JDK 17 or higher
- Visual Studio Code
- Extension Pack for Java (Microsoft)

---

## 🚀 How to Run in VS Code

1. **Install Java**
   - Download & install from:
     - [Adoptium JDK](https://adoptium.net/) or [Oracle JDK](https://www.oracle.com/java/technologies/javase-downloads.html)
   - Verify installation:
     ```bash
     java -version
     javac -version
     ```

2. **Open the project**
   - Save the folder as `JavaToDoApp` with:
     ```
     AdvancedToDoApp.java
     tasks.txt (empty at first)
     README.md
     ```
   - Open VS Code → `File → Open Folder` → select `JavaToDoApp`

3. **Install VS Code Java Extensions**
   - Open Extensions (`Ctrl+Shift+X`)
   - Install **Extension Pack for Java** (Microsoft)

4. **Run the app**
   - **Option A – Run Button:**
     1. Open `AdvancedToDoApp.java`
     2. Click **Run ▶** (top right)
     3. Choose **Run Java File** if prompted
   - **Option B – Terminal:**
     ```bash
     javac AdvancedToDoApp.java
     java AdvancedToDoApp
     ```

---

## 🖥️ How to Use
- **Type a task** in the text field → click **Add Task**
- **Select a task** → click **Mark Completed** to tick it
- **Select a task** → click **Delete Task** to remove it
- Close the app → tasks are saved to `tasks.txt`
- Reopen the app → saved tasks load automatically

---

## 📂 Project Structure
JavaToDoApp/
├── AdvancedToDoApp.java
├── tasks.txt
└── README.md

## 📸 Screenshot

![GUI – ToDo App Screenshot](https://github.com/bclokesh/GUI-ToDo-App/blob/main/Screenshot%202025-08-12%20120634.png)

