User Management System

A simple full-stack application built with Python (Flask), SQLite, HTML, CSS, and JavaScript.

Features

- User registration
- User login
- Display registered users
- Responsive design
- SQLite database

Project Structure

```
.
├── app.py              # Flask backend application
├── requirements.txt    # Python dependencies
├── static/            # Static files
│   ├── css/
│   │   └── style.css  # CSS styles
│   └── js/
│       └── main.js    # Frontend JavaScript
├── templates/         # HTML templates
│   └── index.html    # Main HTML file
└── database.db       # SQLite database (created automatically)
```

## Setup Instructions

1. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   python app.py
   ```

4. Open your browser and navigate to:
   ```
   http://localhost:5000
   ```

## API Endpoints

- `POST /api/register` - Register a new user
- `POST /api/login` - Login user
- `GET /api/users` - Get all registered users

## Security Notes

This is a basic implementation for demonstration purposes. In a production environment, you should:

1. Hash passwords before storing them
2. Implement proper session management
3. Add input validation
4. Use HTTPS
5. Implement rate limiting
6. Add proper error handling #   b u s p a s s 
 
 
