# To-Do List Web App

A simple and responsive **To-Do List Web Application** built using **HTML, CSS, and JavaScript**.
This project allows users to add tasks with a title and description, display them dynamically, and delete tasks when completed.

---

## Features

* Add a task with:

  * Title
  * Description
* Display tasks instantly without page reload
* Delete tasks individually
* Clean and simple UI
* Responsive layout

---

##  Technologies Used

* **HTML5** – Structure of the web page
* **CSS3** – Styling and layout
* **JavaScript (Vanilla JS)** – Dynamic task creation and deletion

---


---

##  How to Run the Project

1. Save the code as **index.html**
2. Open the file in any browser

No installation required ✅

---

##  How It Works

* User enters a **title** and **description**
* Clicks **Save**
* A new task card appears in the task section
* Clicking **X** removes the task

---

##  JavaScript Logic

### Add Task

* Prevents form submission reload using:

```javascript
e.preventDefault();
```

* Creates a new task dynamically:

```javascript
document.createElement("div");
```

### Delete Task

* Removes selected task:

```javascript
task.remove();
```

---

##  UI Components

* Gradient background
* Form box for input
* Task display section
* Delete button for each task

---

##  Future Improvements

* Store tasks in Local Storage
* Edit existing tasks
* Add due date
* Mark task as completed
* Responsive mobile optimization

---

##  License

This project is free to use for learning and personal development.

---

##  Author

Created as a beginner-friendly JavaScript project.
