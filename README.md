# E-Commerce Store REST API

A clean and lightweight RESTful API built with **Python**, **FastAPI**, and **SQLAlchemy** (SQLite). It provides end-to-end functionality for managing products, filtering catalog items, and processing customer orders with automated price calculation.

## Key Features
- **Product Management (CRUD):** Create, view, filter, and remove products from the catalog.
- **Advanced Query Filtering:** Filter products by category and maximum price range.
- **Order Processing:** Create orders linked to products with dynamic `total_price` calculation based on quantity.
- **Persistent Storage:** Uses `SQLAlchemy` ORM with an `SQLite` database (`store.db`).
- **Data Validation & Schemas:** Strictly typed input/output payloads powered by `Pydantic`.
- **Interactive API Documentation:** Built-in Swagger UI for testing endpoints in real-time.

## Tech Stack
- **Language:** Python 3.10+
- **Framework:** FastAPI
- **Database / ORM:** SQLite + SQLAlchemy
- **Data Validation:** Pydantic
- **Server:** Uvicorn

## Project Structure
```text
.
├── main.py              # Main FastAPI application logic and database models
├── store.db             # SQLite database (auto-generated)
├── requirements.txt     # List of project dependencies
└── README.md            # Project documentation
