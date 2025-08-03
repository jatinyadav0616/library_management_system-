# Library Management System

A simple, text-based Library Management System in Python that demonstrates clean coding practices, modular design, and persistent storage. Ideal for learning object-oriented programming, file handling, and basic command-line interfaces.

## Features

- Add Book: Add new books to the library with unique ISBNs.
- Search Book: Find books by title, author, or ISBN.
- View All Books: See all books and their statuses.
- Issue Book: Issue a book (mark as borrowed).
- Return Book: Return a previously issued book (mark as available).
- Persistent Storage: Book data is saved in a `books_db.json` file for persistence.

## How It Works

The system uses two Python classes:
- `Book`: Represents an individual book.
- `Library`: Manages the collection of books, supports all book operations, and handles data persistence.

Books are stored in a JSON file (`books_db.json`) in the same directory as the script.

## Usage

1. **Clone this repository** (or create a new Codespace if using GitHub Codespaces).

2. **Run the application**:
    ```bash
    python library_management_system.py
    ```

3. **Follow the on-screen menu** to manage your library.

## Example Menu

```
===== Library Management System =====
1. Add Book
2. Search Book
3. View All Books
4. Issue Book
5. Return Book
6. Exit
```

## Clean Code and Practices

- Modular OOP design with clear separation of concerns.
- Well-commented methods and classes.
- Exception handling for user-friendly feedback.
- Type hints for readability and maintainability.

## Requirements

- Python 3.7 or higher 
