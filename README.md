# FastAPI Uvicorn Tutorial Project

This project is a tutorial on building web APIs with FastAPI and Uvicorn, based on the Real Python tutorial: [Using FastAPI to Build Python Web APIs](https://realpython.com/fastapi-python-web-apis/#what-is-fastapi).

It demonstrates a simple API setup with Uvicorn.

## Setup

1.  **Clone the repository:**
    ```bash
    git clone <repository_url>
    cd fastapi-tutorial
    ```

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv venv
    ```

3.  **Activate the virtual environment:**
    *   **Windows:**
        ```bash
        .\venv\Scripts\activate
        ```
    *   **macOS/Linux:**
        ```bash
        source venv/bin/activate
        ```

4.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

## Running the application

To run the FastAPI application using Uvicorn, execute the following command:

```bash
uvicorn main:app --reload
```

The API will be accessible at `http://127.0.0.1:8000`.

## Project Structure

-   `main.py`: The main FastAPI application file.
-   `requirements.txt`: Lists all Python dependencies.
-   `.gitignore`: Specifies files and directories to be ignored by Git.
-   `README.md`: This file, providing project information and setup instructions.