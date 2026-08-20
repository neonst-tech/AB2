# AB2 — Property Listing & Rental Management Platform

Starter repository for the **Property Listing & Rental Management Platform** project.

This repository intentionally contains only the basic Django project and application structure needed to begin development. The project requirements are provided separately by Neonst.

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/neonst-tech/AB2.git
cd AB2
```

### 2. Create and activate a virtual environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run initial Django migrations

```bash
python manage.py migrate
```

### 5. Start the development server

```bash
python manage.py runserver
```

Open `http://127.0.0.1:8000/` in your browser.

## Project Structure

```text
AB2/
├── properties/         # Main Django application
├── config/             # Django project configuration
├── templates/          # Shared HTML templates
├── static/             # Static assets
├── manage.py
├── requirements.txt
└── README.md
```

## Development Notes

- The application uses Django.
- SQLite is configured as the initial development database.
- Bootstrap and the application UI should be added as part of development.
- Data models, authentication, property listings, image handling, search/filtering, inquiries, favorites, views, URLs, templates, validation, and business rules are intentionally left for implementation from the project requirements.
- Do not commit the virtual environment or secret configuration files.

## Before Submission

- Test the application from a clean environment.
- Make sure all required pages and navigation work.
- Make sure forms perform appropriate validation.
- Include database migration files.
- Remove unused files and code.
- Add screenshots of the completed application as requested in the project requirements.
