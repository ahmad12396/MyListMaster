🚀 MY List Master | Pro Dashboard
MY List Master is a sleek, modern task management web application built with Django and Bootstrap 5. It provides a high-performance user interface with real-time frontend validation, persistent task tracking, and a beautiful responsive design.

✨ Key Features
Dual-Column Management: Separate sections for "Pending" and "Completed" tasks for better organization.

Duplicate Prevention: Advanced JavaScript validation prevents adding the same task twice to your pending list.

Pro UI/UX:

Glassmorphism design with backdrop filters.

Centered interactive action icons for a balanced look.

Animated "Pulse" heart icon and hover effects.

Custom slim scrollbars for a clean look.

Responsive Design: Fully optimized for mobile, tablet, and desktop views.

Smart Date Tracking: Displays the current date dynamically using Django’s template tags.

🛠️ Tech Stack
Backend: Python 3.x, Django 5.x

Frontend: HTML5, CSS3 (Flexbox/Grid), JavaScript (ES6+)

Styling: Bootstrap 5, Font Awesome 4.7, Google Fonts (Inter)

Database: SQLite (Default)

📦 Installation & Setup
Clone the repository:

Bash
git clone https://github.com/yourusername/my-list-master.git
cd my-list-master
Create a Virtual Environment:

Bash
python -m venv venv
# Windows
venv\Scripts\activate
# Mac/Linux
source venv/bin/activate
Install Dependencies:

Bash
pip install django
Database Migrations:

Bash
python manage.py makemigrations
python manage.py migrate
Run the Server:

Bash
python manage.py runserver
Access the app at http://127.0.0.1:8000/.

⚙️ How It Works
The project follows the standard Django MVT (Model-View-Template) architecture:

Models: Handles the database schema (Task name, Status, Created date).

Views: Contains the logic for adding, marking as done/undone, and deleting tasks from the database.

Frontend Validation: The home.html includes a JavaScript listener that checks your current pending list before submission. If the task already exists, it blocks the request and shows a warning, reducing unnecessary server calls.

🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page.

✍️ Author
Ghafeer Ahmad

LinkedIn: https://www.linkedin.com/in/ghafeer/

GitHub: https://github.com/ahmad12396
