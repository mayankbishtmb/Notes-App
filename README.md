📝 Notes App

A clean and minimal multi-tab Notes Management App built using modern frontend technologies.
This app allows users to create, organize, search, archive, and manage notes efficiently — all powered by Local Storage (no backend required).


🔗 https://github.com/mayankbishtmb/Notes-App

✨ Features

📝 Create, edit, and delete notes

📂 Multi-tab view:

Active Notes

Archived Notes

Trash

🔍 Real-time Search functionality

♻️ Restore notes from Archive or Trash

🗑️ Permanent delete from Trash

💾 Persistent data using Browser LocalStorage

⚡ Instant UI updates without page reload

📱 Responsive Design (Mobile + Desktop)

🧠 How It Works

This application uses Local Storage to simulate a backend database.

All notes are stored as JSON in the browser.

Each note contains:

id

title

content

createdAt

isArchived

isDeleted

Data is filtered dynamically based on state to show:

Active notes → !isArchived && !isDeleted

Archived notes → isArchived

Trash notes → isDeleted

Search works by filtering notes based on title/content match.

🛠️ Tech Stack

HTML5

CSS3

JavaScript (ES6+)

LocalStorage API

(If you used React, replace with React, Hooks, etc.)

📂 Folder Structure
notes-app/
│
├── index.html
├── style.css
├── script.js
├── assets/
└── README.md
📸 Screenshots

Add screenshots here for better presentation.

1️⃣ Create Note

User enters title & content

Unique ID generated

Saved in LocalStorage

UI updates instantly

2️⃣ Archive Note

Moves note from Active → Archive

Updates state flag

3️⃣ Move to Trash

Soft delete functionality

Note can be restored

4️⃣ Search

Filters notes dynamically

Case-insensitive matching

📌 Why LocalStorage?

No backend needed

Fast and simple

Perfect for small productivity apps

Great for understanding state management

🧪 Future Improvements

🌙 Dark Mode

🏷️ Add Tags & Categories

☁️ Cloud Sync (Firebase / Backend)

🔐 Authentication

📅 Sorting & Filtering Options

🧠 Rich Text Editor

🎯 Learning Outcomes

Through this project, I practiced:

DOM manipulation

State management without backend

Filtering and array methods

UI state separation (Active / Archive / Trash)

Search logic implementation

Clean component-based thinking (if React used)

📄 License

This project is open-source and available under the MIT License.
