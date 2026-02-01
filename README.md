# 📌 Cross-Platform To-Do List App

A simple cross-platform to-do list application built using **React Native**. This project demonstrates how a single shared codebase can be used to create a functional mobile application that runs on both Android and iOS.

---

## 🛠 Framework Used

* **React Native**
* JavaScript / TypeScript
* Runs on Android and iOS from a single codebase

---

## ⚖ Native vs Cross-Platform (Brief Comparison)

**Native Development** involves building separate applications for each platform (e.g., Kotlin for Android and Swift for iOS), which can result in better performance but higher development time and maintenance cost.

**Cross-Platform Development**, such as React Native, allows developers to write one shared codebase that works across multiple platforms. This reduces development time, simplifies maintenance, and is ideal for small to medium-sized applications like this to-do list app.

---

## 📋 App Features

The application includes the following features:

* Text input field to enter new tasks
* Button to add tasks to the list
* List view displaying all added tasks
* Ability to delete tasks from the list
* Single-screen, clean, and simple user interface

---

## 📱 Screenshots

Screenshots of the running application are included in the `screenshots/` folder:

* `add_task.png` – Adding a new task
* `task_list.png` – Displaying the list of tasks
* `delete_task.png` – Removing a task

---

## 📂 Project Structure

```
MobileDev-StudentName/
│
├── app/
│   └── React Native source code
├── screenshots/
│   ├── add_task.png
│   ├── task_list.png
│   └── delete_task.png
├── README.md
```

---

## 🚀 How to Run the App

1. Clone this repository
2. Open the project folder
3. Install dependencies:

   ```bash
   npm install
   ```
4. Start the development server:

   ```bash
   npm start
   ```
5. Run the app on an Android emulator, iOS simulator, or physical device

---

## ⚠ Common Pitfalls Avoided

* Used only React Native components (no unnecessary native code)
* Kept the app scope simple and focused
* Managed task list state properly using React state
* Included all required screenshots and documentation


---

## 📄 License

This project is for educational purposes only.
