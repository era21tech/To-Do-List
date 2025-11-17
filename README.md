# To-Do-List
A simple and clean To-Do List web app built with HTML, CSS, and JavaScript. Supports adding, checking, and deleting tasks with automatic localStorage saving so your tasks stay even after refresh. Perfect beginner-friendly productivity app.


## 🚀 **Features**

* ✔ Add new tasks
* ✔ Mark tasks as completed
* ✔ Delete tasks
* ✔ Auto-save using Local Storage
* ✔ Smooth and clean UI
* ✔ Mobile-responsive layout

---

## 🛠 **Tech Stack**

* **HTML5**
* **CSS3** (Simple, modern UI)
* **JavaScript (vanilla)**

---

## 📂 **Project Structure**

```
📁 project-folder
│── index.html
│── style.css
│── script.js
└── /images
       ├── icon.png
       ├── checked.png
       └── unchecked.png
```

---

## 📸 **Screenshots**

(Add screenshots here once uploaded)

---

## 📥 **How to Use**

1. Clone this repository:

   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Open the folder.
3. Run `index.html` in your browser.
4. Start adding your daily tasks!

---

## 💾 **Local Storage (How it works)**

The app saves tasks using:

```javascript
localStorage.setItem("data", listContainer.innerHTML);
```

And loads tasks using:

```javascript
listContainer.innerHTML = localStorage.getItem("data");
```

This keeps your tasks safe even after refreshing.

---

## 🤝 **Contributing**

Feel free to fork this project and submit pull requests to enhance features or improve UI.

---

## ⭐ **If you like this project**

Don’t forget to **star ⭐ this repo** — it motivates me to build more projects!

---




