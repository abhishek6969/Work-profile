# My Flask App

This is a personal resume-type profile application built using Flask. It showcases the user's information, skills, and experience.

## Project Structure

```
my-flask-app
├── app
│   ├── __init__.py
│   ├── routes.py
│   └── templates
│       └── index.html
├── run.py
├── requirements.txt
└── README.md
```

## Setup Instructions

1. **Clone the repository:**
   ```
   git clone <repository-url>
   cd my-flask-app
   ```

2. **Create a virtual environment:**
   ```
   python -m venv venv
   ```

3. **Activate the virtual environment:**
   - On Windows:
     ```
     venv\Scripts\activate
     ```
   - On macOS/Linux:
     ```
     source venv/bin/activate
     ```

4. **Install the required dependencies:**
   ```
   pip install -r requirements.txt
   ```

## Running the Application

To start the Flask application, run the following command:

```
python run.py
```

The application will be accessible at `http://localhost:5000`.

## Features

- Home page displaying personal information
- Skills and experience sections
- Responsive design for better viewing on different devices

## License

This project is licensed under the MIT License.