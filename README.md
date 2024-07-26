# Simple Search Engine

This project is a simple search engine that ranks documents using a vector space model and cosine similarity. The web application is built with Django and leverages various Python libraries for document processing and ranking.

## Features

- Indexes and searches documents
- Ranks documents using vector space model and cosine similarity
- Web-based interface for querying and displaying results

## Technologies Used

- Django (Python)
- Numpy
- Scikit-learn
- NLTK
- PyPDF2
- Python-docx

## Prerequisites

- Python

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/saleamlakw/Search_it.git
    cd Search_it
    ```

2. Create a virtual environment and activate it:

    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required Python packages:

    ```bash
    pip install -r requirements.txt
    ```

4. Install frontend dependencies (if any):

    ```bash
    npm install
    ```

5. Apply the database migrations:

    ```bash
    python manage.py migrate
    ```

6. Create a superuser to access the admin panel:

    ```bash
    python manage.py createsuperuser
    ```

7. Collect static files:

    ```bash
    python manage.py collectstatic
    ```

## Running the Development Server

Start the Django development server:

```bash
python manage.py runserver
```
## Visit http://127.0.0.1:8000/ in your web browser to see the application in action.
