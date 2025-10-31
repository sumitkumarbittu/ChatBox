# Dexter - Text Submission and Management System

## 🌟 Overview
Dexter is a full-stack web application that allows users to submit, store, and manage text entries. It features a clean, responsive interface and robust backend functionality for text management.

## 🚀 Features

### User Experience
- **Intuitive Interface**: Clean, modern design with responsive layout
- **Real-time Updates**: Submissions appear instantly without page reload
- **User Identification**: Optional name field for personalization
- **Word Count**: Automatic word count for each submission
- **Timestamping**: Entries are automatically time-stamped

### Technical Capabilities
- **RESTful API**: Built with Flask for backend operations
- **Database Integration**: PostgreSQL for reliable data storage
- **CORS Support**: For secure cross-origin requests
- **Responsive Design**: Works on desktop and mobile devices
- **Asynchronous Operations**: Smooth user experience with async JavaScript

### Data Management
- **CRUD Operations**: Full Create, Read, Update, Delete functionality
- **Persistent Storage**: Entries are stored in a PostgreSQL database
- **Data Validation**: Server-side input validation
- **Bulk Operations**: Clear all entries with a single click

## 🛠️ Technical Stack

### Backend
- **Framework**: Flask (Python)
- **Database**: PostgreSQL
- **API**: RESTful endpoints
- **Authentication**: Basic request validation
- **Deployment**: Render (PaaS)

### Frontend
- **HTML5**: Semantic markup
- **CSS3**: Custom styling with responsive design
- **JavaScript**: Vanilla JS for dynamic content
- **AJAX**: For seamless data fetching and submission

### Dependencies
- Flask
- psycopg2-binary
- Flask-CORS
- gunicorn (Production server)
- SQLAlchemy (ORM)

## 🚀 Getting Started

### Prerequisites
- Python 3.7+
- PostgreSQL database
- pip (Python package manager)

### Installation
1. Clone the repository
2. Create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: .\venv\Scripts\activate
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Set up environment variables:
   ```
   export DATABASE_URL=your_database_connection_string
   ```
5. Initialize the database:
   ```bash
   flask --app app.py init_db
   ```
6. Run the application:
   ```bash
   python app.py
   ```

## 🌐 API Endpoints

- `GET /` - Serve the main interface
- `POST /submit` - Submit a new text entry
- `GET /history` - Retrieve all entries
- `POST /delete/<id>` - Delete a specific entry
- `POST /clear_db` - Clear all entries (Use with caution!)

## 📱 Usage
1. Open the application in your web browser
2. Enter your name (optional) and your text in the provided fields
3. Click "Submit" to save your entry
4. View all submissions in the history section
5. Delete individual entries as needed

## 🔒 Security Features
- Input sanitization
- CSRF protection (recommended for production)
- Secure database connection with SSL
- Environment-based configuration

## 📊 Future Enhancements
- User authentication and authorization
- Text analysis features
- Rich text editing capabilities
- Export functionality (CSV, PDF)
- Search and filter functionality
- User profiles and preferences

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments
- Built with Flask and PostgreSQL
- Deployed on Render
- Inspired by simple yet effective web applications Dexter1