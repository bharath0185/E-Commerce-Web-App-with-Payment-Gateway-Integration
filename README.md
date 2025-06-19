# 🛒 E-Commerce Web App with Payment Gateway Integration

This is a lightweight, responsive e-commerce web application that allows users to browse products, add them to a cart, and proceed to checkout with or without logging in. The app features a secure payment gateway using Stripe.

## 🚀 Features

- Product catalog with images and pricing  
- Add-to-cart and cart management  
- Guest checkout (no login required)  
- Optional user authentication  
- Secure payment integration using Stripe  
- Responsive UI styled with Bootstrap  

## 🛠️ Tech Stack

- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Backend:** Python, Django  
- **Database:** SQLite  
- **Payment Gateway:** Stripe  

## 📦 Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/e-commerce-web-app.git
   cd e-commerce-web-app

2. **Create virtual environment**
python -m venv env
source env/bin/activate        # On Windows: env\Scripts\activate

3. **Install dependencies**
pip install -r requirements.txt

4. **Set up Stripe environment variables (create a .env file)**
echo "STRIPE_PUBLIC_KEY=your_publishable_key" >> .env
echo "STRIPE_SECRET_KEY=your_secret_key" >> .env

5. **Apply migrations**
python manage.py migrate

6. **Run development server**
python manage.py runserver
