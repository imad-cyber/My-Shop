# My-Shop
From the Book of Django5 by example by Antonio MELE

# Django E-Commerce Backend (Django 5)

A full-featured e-commerce backend system built with Django 5, implementing real-world shopping cart, order management, and payment workflows.

---

## Features

- Product catalog with categories and filtering
- Session-based shopping cart
- Persistent cart storage in database
- Order creation and lifecycle management
- Payment flow simulation (Stripe-style architecture)
- Admin dashboard for product & order management
- Stock/inventory tracking

---

## What I Learned

- Designing stateful systems (cart → order → payment flow)
- Handling session vs database persistence trade-offs
- Structuring scalable Django models
- Avoiding ORM performance pitfalls (N+1 queries)
- Managing real-world backend workflows

---

## Tech Stack

- Python 3
- Django 5
- SQLite / PostgreSQL
- Django ORM
- HTML templates (basic frontend)

---

## Project Structure
shop/
│── cart/
│── orders/
│── products/
│── payments/
│── templates/


---

## ⚙️ Setup Instructions

```bash
git clone <repo-url>
cd project

python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate

pip install -r requirements.txt

python manage.py migrate
python manage.py runserver
