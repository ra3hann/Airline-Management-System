# Airline Management System (AMS)

## Overview
The Airline Management System (AMS) is a web-based application built to streamline airline operations by managing flight and passenger data. This platform enables efficient storage, retrieval, and management of passenger details and flight schedules, allowing airline staff to handle day-to-day tasks smoothly. The system is developed using Flask, with a focus on modular design and ease of use.

## Features
### Passenger Module
- **Passenger Management**: Store and manage passenger information, including name, age, gender, contact information, and email.
- **Data Entry**: Easily add new passenger records.
- **Record Deletion**: Delete passenger records as required for efficient data management.

### Flight Module
- **Flight Scheduling**: Manage flight schedules, including origin, destination, departure and arrival times.
- **Flexible Data Management**: Add, update, or delete flight records to keep schedules up-to-date.

## Tech Stack
- **Backend**: Flask (Python)
- **Frontend**: HTML/CSS (with inline CSS for simplicity)
- **Database**: SQLite

## Project Structure
- `app.py`: The main application file, handling routing, database interactions, and application logic.
- `templates/`: HTML files for rendering web pages.
    - `index.html`: Home page for navigation.
    - `passengers.html`: Display and manage passenger information.
    - `flights.html`: Display and manage flight schedules.
- `airline.db`: SQLite database storing flight and passenger records.

## Setup Instructions
1. Clone this repository:
   ```bash
   git clone <repo_url>
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Flask application:
   ```bash
   python app.py
   ```
4. Access the application at `http://localhost:8000`.

## Future Enhancements
- Implement search and filter functionality for passenger and flight records.
- Add authentication to manage roles (e.g., admin vs. regular staff).
- Extend database integration for larger data handling capabilities.

## License
This project is open-source under the MIT License.
