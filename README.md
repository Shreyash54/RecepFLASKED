🍽️ RecipesByEagles
A simple Flask-based Recipe Management System that allows users to log in, browse recipes by category, view recipe details with images, add comments, search recipes, and manage recipes securely.

🚀 Features

🔐 User Authentication

Secure login using SHA-256 password hashing

Session-based authentication

📂 Recipe Categories

Recipes are organized by categories

📖 Recipe Management

Add recipes with ingredients, instructions, and images

Delete recipes by name

🖼️ Image Handling

Store and serve recipe images from the database (BLOB)

Fallback image if none is available

💬 Comments System

Logged-in users can comment on recipes

Comments are timestamped

🔍 Search & Suggestions

Search recipes by exact name

Auto-suggestions using partial matches

🗄️ SQLite Database

Lightweight and easy to set up

⚠️ Flash Messages

User-friendly success/error notifications

🛠️ Tech Stack

Backend: Flask (Python)

Database: SQLite3

Frontend: HTML, Jinja2 Templates

Security: SHA-256 password hashing


⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/recipe-app.git
cd recipe-app

2️⃣ Create a Virtual Environment (Optional but Recommended)
python -m venv venv
source venv/bin/activate   # On Windows: venv\Scripts\activate

3️⃣ Install Dependencies
pip install flask

4️⃣ Run the Application
python app.py


The app will start at:

http://127.0.0.1:5000/
