# Django E-Commerce

This project provides a basic e-commerce site built with the Django web framework. It includes modules for managing products, a shopping cart, and a minimal payment flow. The default database is SQLite and media files are stored locally.

## Getting started

1. **Clone the repository**
   ```bash
   git clone <repo-url>
   cd Django-Ecommerce
   ```
2. **Create a virtual environment** (recommended)
   ```bash
   python -m venv venv
   source venv/bin/activate
   ```
3. **Install dependencies**
   ```bash
   pip install Django==4.2.7 Pillow
   ```
4. **Apply database migrations**
   ```bash
   python manage.py migrate
   ```
5. **Create an admin user**
   ```bash
   python manage.py createsuperuser
   ```
6. **Start the development server**
   ```bash
   python manage.py runserver
   ```
7. Open `http://127.0.0.1:8000/` in your browser to view the site.

## Project layout

- `store/` – product catalog and user profile logic
- `cart/` – shopping cart functionality
- `payment/` – simple checkout and order processing
- `ecom/` – project configuration and URLs

The templates for each app live under their respective `templates/` directories.

## Running tests

The repository includes placeholder test files. Run them with:
```bash
python manage.py test
```

## Notes

This project is intended as a learning example. You can customize the models and templates to fit your own requirements.

