# 🛒 Grocery Management System

A web-based Grocery Management System built using Django that helps manage products, inventory, and user interactions efficiently. This system is designed to simplify grocery store operations with a scalable and structured backend.

---

## 🚀 Features

- 🔐 Custom User Authentication System  
- 📦 Product / Item Management  
- 🖼️ Image Upload for Products  
- 📊 Inventory & Quantity Tracking  
- ✅ Admin Approval System for Items  
- 🌐 Public Item Listing  
- ⚙️ Clean and Scalable Django Backend  

---

## 🛠️ Tech Stack

- **Backend:** Python, Django  
- **Frontend:** HTML, CSS  
- **Database:** SQLite (default)  
- **Media Handling:** Django Media Files  

---

## 📂 Project Structure
grocery-management/
│── grocery_app/
│ ├── models.py
│ ├── views.py
│ ├── admin.py
│ ├── urls.py
│
│── templates/
│── static/
│── media/
│── manage.py
│── requirements.txt


---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/grocery-management.git
cd grocery-management

python -m venv env
source env/bin/activate   # Mac/Linux
env\Scripts\activate      # Windows

pip install -r requirements.txt

python manage.py makemigrations
python manage.py migrate

python manage.py createsuperuser

python manage.py runserver
