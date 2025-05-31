# Blood Donation Management System

A simple web application for managing blood donors, blood requests, and blood inventory, built with Flask and SQLite.

## Features

- Register as a blood donor
- Request blood by blood group
- View current blood inventory and pending requests
- Responsive UI with a clean design

## Project Structure

```
app.py
database.py
blood_bank.db
static/
    style.css
templates/
    index.html
    register.html
    request.html
    inventory.html
```

## Getting Started

### Prerequisites

- Python 3.x
- Flask (`pip install flask`)

### Running the Application

1. Clone the repository.
2. Install dependencies:
    ```sh
    pip install flask
    ```
3. Run the app:
    ```sh
    python app.py
    ```
4. Open your browser and go to `http://127.0.0.1:5000/`

## File Descriptions

- [`app.py`](app.py): Main Flask application with route definitions.
- [`database.py`](database.py): Database initialization and helper functions.
- [`templates/`](templates/): HTML templates for the web pages.
- [`static/style.css`](static/style.css): CSS styles for the application.

## License

This project is licensed under the MIT License.
