# Final Chatbot

A chatbot application with a Python backend and a frontend built with HTML, CSS, and JavaScript.

## Features
- Python-based backend
- Database population script
- Simple frontend with HTML, CSS, and JS

## Installation

### Prerequisites
- Python 3.x
- Node.js (for database population script, if needed)
- Flask (for backend)

### Steps
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/final_chatbot.git
   cd final_chatbot
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the backend server:
   ```sh
   python app.py
   ```
4. Open `index.html` in a browser to access the frontend.

## Database Population
If your application requires a database, run the following command:
```sh
node populate_db.js
```

## File Structure
```
final_chatbot/
│── app.py               # Backend server
│── populate_db.js       # Database script
│── frontend/
│   ├── index.html       # Main frontend file
│   ├── styles.css       # Stylesheet
│   ├── script.js        # Frontend logic
│   ├── logo.jpg         # Logo image
│   ├── bitm1.jpg        # Additional image
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the MIT License.
