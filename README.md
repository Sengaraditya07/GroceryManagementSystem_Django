🛒 Grocery Management System

A web-based Grocery Management System built using Django that helps manage products, inventory, and user interactions efficiently. This system is designed to simplify grocery store operations with a scalable and structured backend.

🚀 Features
🔐 Custom User Authentication System
📦 Product / Item Management
🖼️ Image Upload for Products
📊 Inventory & Quantity Tracking
✅ Admin Approval System for Items
🌐 Public Item Listing
⚙️ Clean and Scalable Django Backend
🛠️ Tech Stack
Backend: Python, Django
Frontend: HTML, CSS
Database: SQLite (default)
Media Handling: Django Media Files
📂 Project Structure
grocery-management/
│── grocery_app/
│   ├── models.py
│   ├── views.py
│   ├── admin.py
│   ├── urls.py
│
│── templates/
│── static/
│── media/
│── manage.py
│── requirements.txt
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/grocery-management.git
cd grocery-management
2️⃣ Create Virtual Environment
python -m venv env
source env/bin/activate   # Mac/Linux
env\Scripts\activate      # Windows
3️⃣ Install Dependencies
pip install -r requirements.txt
4️⃣ Apply Migrations
python manage.py makemigrations
python manage.py migrate
5️⃣ Create Superuser
python manage.py createsuperuser
6️⃣ Run Server
python manage.py runserver
🌐 Usage
Visit: http://127.0.0.1:8000/
Admin Panel: http://127.0.0.1:8000/admin/
Add products, manage inventory, and approve items via admin panel
📸 Screenshots

Add screenshots of your project here

🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

📄 License

This project is open-source and available under the MIT License.

👨‍💻 Author

Aditya Sengar

GitHub: https://github.com/Sengaraditya07
