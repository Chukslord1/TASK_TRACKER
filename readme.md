# Python API Example

This is a simple Python API example using Flask and SQLite. The API provides an endpoint to add tasks and serves a static HTML page to interact with the API.

## Prerequisites

- Python 3.x installed
- `pip` installed

## Setup

1. Clone the repository:

    ```bash
    git clone <repository_url>
    cd <repository_name>
    ```

2. Create and activate a virtual environment:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Run the application:

    ```bash
    python app.py
    ```

5. Open your browser and navigate to `http://localhost:5000` to interact with the app.

## Endpoints

- `GET /`: Serves the static HTML page.
- `POST /add_task`: Adds a new task to the list.