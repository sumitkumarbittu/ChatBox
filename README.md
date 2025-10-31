# ChatBox - Real-time Messaging Platform

## 🌟 Overview
ChatBox is a real-time messaging platform that enables users to exchange messages instantly. Built with Flask and modern web technologies, it offers a seamless chat experience with a clean, responsive interface.

## 🚀 Features

### User Experience
- **Real-time Messaging**: Instant message delivery with WebSocket support
- **User Presence**: See who's online and available to chat
- **Message History**: View and search through past conversations
- **Responsive Design**: Works seamlessly across all devices
- **Read Receipts**: Know when your messages are seen

### Technical Capabilities
- **RESTful API**: Built with Flask for backend operations
- **Database Integration**: PostgreSQL for reliable data storage
- **CORS Support**: For secure cross-origin requests
- **Responsive Design**: Works on desktop and mobile devices
- **Asynchronous Operations**: Smooth user experience with async JavaScript

### Data Management
- **End-to-End Encryption**: Secure message transmission
- **Message Persistence**: Never lose your chat history
- **Media Sharing**: Share images, files, and more
- **Message Search**: Quickly find conversations and content

## 🛠️ Technical Stack

### Backend
- **Framework**: Flask (Python)
- **Database**: PostgreSQL
- **API**: RESTful endpoints
- **Authentication**: Basic request validation
- **Deployment**: Render (PaaS)

### Frontend
- **Modern UI/UX**: Built with responsive design principles
- **Real-time Updates**: Using WebSockets for instant messaging
- **Interactive Elements**: Emoji picker, file uploads, and more
- **Progressive Web App**: Works offline and installable

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

- `GET /` - Serve the chat interface
- `POST /api/messages` - Send a new message
- `GET /api/messages` - Retrieve message history
- `POST /api/messages/delete` - Delete a message
- `WS /ws` - WebSocket endpoint for real-time updates

## 📱 Getting Started
1. Open ChatBox in your web browser
2. Sign up or log in to your account
3. Start a new conversation or join an existing one
4. Send messages, share files, and enjoy real-time communication
5. Manage your conversations and settings as needed

## 🔒 Security Features
- Input sanitization
- CSRF protection (recommended for production)
- Secure database connection with SSL
- Environment-based configuration

## 📊 Future Enhancements
- Group chats and channels
- Voice and video calling
- Message reactions and replies
- Custom emojis and stickers
- Message scheduling
- Advanced search with filters
- Integration with other services
- End-to-end encryption

## 🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments
- Built with Flask, WebSockets, and PostgreSQL
- Deployed on Render
- Inspired by modern messaging platforms like WhatsApp and Telegram