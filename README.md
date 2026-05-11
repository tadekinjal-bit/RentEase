# 🛍️ RentEase — Buy, Sell or Rent

> A full-stack e-commerce web platform where users can **buy OR rent** products — built with Python & Django.

---

## 💡 About The Project

Most e-commerce platforms only let you **buy** products. RentEase is different.

RentEase gives users the flexibility to either **buy** a product outright or **rent** it for a specific period — making it affordable for buyers and more profitable for sellers. Whether it's vehicles, electronics, clothes, or cameras — everything is available to rent or buy in one place.

**The problem it solves:**
- Buyers don't always want to purchase expensive items permanently (e.g. a Royal Enfield for a weekend trip).
- Sellers can earn recurring rental income instead of one-time sale income.
- RentEase connects both — making transactions simple, transparent, and flexible.

---

## 🚀 Features

### 👤 User Roles
- **Buyer** — Browse, rent, or buy products; track active rentals and purchases
- **Seller** — List products with both rent/day and buy price; track sold and rented items
- **Admin** — Full control over all products, rentals, and users

### 🛒 Buyer Features
- Sign up / Login as a Buyer
- Browse products across categories (Clothes, Electronics, Vehicles, Cameras, etc.)
- **Buy a product** — select quantity, size, delivery address, and pay via Razorpay
- **Rent a product** — select start date and end date; price calculated per day
- Buyer Dashboard — view currently rented items, purchased items, and return history
- Return rented items directly from dashboard

### 🏪 Seller Features
- Sign up / Login as a Seller
- Add products with: name, category, rent price (₹/day), buy price, quantity, and image
- Seller Dashboard — view total products, items sold, items currently rented
- Track all sold products with buyer info, revenue, and date
- Track all rented products with active/returned status

### 🔧 Admin Features
- Admin login panel
- View all rented items across the platform with start date, end date, total price, and return status (Active / Returned)
- Full oversight of platform activity

### 🌐 Other Pages
- Home page with "How It Works" section and user reviews
- About Us page with platform story and features
- Contact Us page with inquiry form
- Multi-language toggle (English)

---

## 🖼️ Screenshots

### Home Page
![Home Page](screenshots/home_page.jpeg)

### Buyer Dashboard
![Buyer Dashboard](screenshots/buyer_dashboard.jpeg)

### Seller Dashboard
![Seller Dashboard](screenshots/seller_dashboard.jpeg)

### Admin — All Rented Products
![Admin Rented](screenshots/admin_rented_page.jpeg)

### Buy Product Page
![Buy Product](screenshots/Buy_Product_.jpeg)

### Seller — Add Product
![Add Product](screenshots/seller_add_product_page.jpeg)

### Seller — All Products
![All Products](screenshots/seller_all_product.jpeg)

### Buyer Signup
![Signup](screenshots/buyer_signup.jpeg)

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Backend | Python, Django |
| Frontend | HTML, CSS, JavaScript |
| Database | SQLite (Django default) |
| Payment | Razorpay Integration |
| IDE | PyCharm |

---

## ⚙️ How To Run Locally

```bash
# 1. Clone the repository
git clone https://github.com/yourusername/rentease.git
cd rentease

# 2. Create a virtual environment
python -m venv env
source env/bin/activate  # On Windows: env\Scripts\activate

# 3. Install dependencies
pip install -r requirements.txt

# 4. Run migrations
python manage.py migrate

# 5. Start the development server
python manage.py runserver
```

Then open your browser and go to: `http://127.0.0.1:8000`

---

## 📁 Project Structure

```
rentease/
├── manage.py
├── rentease/          # Main Django project settings
├── products/          # Product listing, rent, buy logic
├── users/             # Buyer, Seller, Admin authentication
├── templates/         # HTML templates
├── static/            # CSS, JS, Images
└── screenshots/       # Project screenshots
```

---

## 👩‍💻 Developer

**Kinjal Tade**  
B.E. Computer Science & Engineering  
New LJ Institute of Engineering and Technology, Ahmedabad  
📧 tadekinjal@gmail.com  
📱 9904407737

---

## 📄 License

This project was built as part of a 3-month internship at **Sparks to Ideas, Ahmedabad** (Completed: April 2026).

---

> *"RentEase — because not everything needs to be bought."*
