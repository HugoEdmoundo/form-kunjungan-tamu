📄 Guest Visit Form
Guest Visit Form is a simple web-based application built with HTML, CSS, and JavaScript for digitally recording guest information. This project is fully frontend-only — it does not use any backend or external database. All data is stored locally (in-memory or optionally using localStorage).

Perfect for internal or offline use in offices, schools, or institutions to replace traditional paper guest books.

✨ Features
✅ Guest data input form (name, organization, purpose, etc.)

✅ Basic form validation

✅ Modern, responsive UI (using Bootstrap)

✅ Optional table to display submitted data

✅ Local data handling (in-memory or via localStorage)

✅ Ready to extend with features like export to Excel or PDF

🛠 Technologies Used
HTML5

CSS3 (Bootstrap 5)

JavaScript (Vanilla JS)

📁 Project Structure

guest-visit-form/
├── index.html        → Main form page
├── style.css         → Custom CSS styling
├── script.js         → JavaScript logic
├── background.jpg    → Background image
├── logo.png          → Logo image
└── README.md         → Project documentation
🚀 How to Run
Download or clone this repository:

git clone https://github.com/HugoEdmoundo/form-kunjungan-tamu.git
Open the folder:

cd guest-visit-form
Launch the form in your browser:

Double-click index.html, or

Open with Live Server in VS Code

🧪 How It Works
Guest fills out the form:

Full name

Purpose of visit

ID information

Take a photo (if implemented)

Click Submit.

The data is validated and displayed in the form/table (stored only locally).

Note: This project does not connect to any server or backend — data will be lost on refresh unless localStorage is used.

🔒 Security Note
Since there's no backend, this app is intended for offline or controlled-use scenarios. Do not use it to collect sensitive personal data in production.

📌 Future Improvements (Optional)
 Export data to Excel or PDF

 Save data using localStorage

 Add photo capture with webcam (via JavaScript)

 Print visit receipts

📃 License
This project is open-source and free to use for personal or educational purposes. You may modify or extend it as needed. Redistribution or resale of the original version is not allowed without permission.

