# 🍽️ SLM House Menu

**SLM House Menu** is a web-based application built to help manage meals, members, and budgeting within a shared household, hostel, or small community. It includes features for adding, editing, deleting meals and member profiles, data visualization using charts, and a responsive, accessible UI.

---

## 📊 Features

- **Meal Management**: Add, edit, and delete meals using modal forms.
- **Member Profiles**: Add and update member profiles with avatar support.
- **Analytics Dashboard**: View meal distribution and budget stats with Chart.js.
- **Interactive UI**: SweetAlert popups, keyboard navigation, and ARIA accessibility.
- **Persistent Storage**: Uses `localStorage` with options to upgrade to Firebase, MySQL, or Express backend.
- **Modern Design**: Clean, responsive layout with animations and dynamic updates.

---

## 🧱 Project Structure

```bash
slm-house-menu/
├── Menu.html               # Main application file
├── 
├── assets/
│   └── avatar-default.png   # Default member avatar
├──
└── README.md                # This documentation file

🚀 Getting Started
✅ Prerequisites
A modern browser (Chrome, Firefox, Edge)

Optionally, a simple HTTP server for local development (like Live Server or http-server)

💻 Run Locally
Clone this repo:
git clone https://github.com/Hedmon0094/SLM House-Menu.git
cd SLM-House-Menu

Open Menu.html in your browser:
On VS Code: Right-click index.html → Open with Live Server

Or double-click the file directly

⚙️ Core Functionalities
📝 Meals
Add Meal: Opens modal with form fields

Edit Meal: Pre-fills form for editing

Delete Meal: Confirmation via SweetAlert before deletion

LocalStorage: Meals are stored locally (persistent across refreshes)

👥 Members
Add/Edit Members: Modal form including name, avatar (image upload), and role

Avatar Upload: Fallback to default image if not selected

📈 Analytics Dashboard
Built using Chart.js

Displays:

Meal count per member

Budget analysis (monthly/weekly)

Updates dynamically with user interaction

🛠️ Tech Stack
Technology	Use Case
HTML5/CSS3	UI Layout & Styling
JavaScript	Functionality & Interactivity
Chart.js	Data Visualization
SweetAlert2	Stylish modal alerts
localStorage	Persistent frontend data storage
ARIA	Accessibility & screen reader support

📌 Roadmap
 🔐 Add role-based user authentication

 ☁️ Connect to Firebase or Express + MySQL backend

 📤 Export meal data as PDF or Excel reports

 🔔 Notifications for upcoming meals or budget limits

 🔄 Drag-and-drop meal reordering

🧑‍💻 Contributing
Contributions are welcome!

Fork the repository

Create a new feature branch: git checkout -b feature-name

Commit your changes: git commit -m 'Add some feature'

Push to the branch: git push origin feature-name

Open a Pull Request



🙏 Acknowledgements
Built with ❤️ by AmonSoftwares LTD
Maintained by @Hedmon0094

For demo, support, or feature requests, feel free to open an issue.

