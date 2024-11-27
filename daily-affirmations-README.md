
# Daily Affirmations App

A simple web app to deliver motivational quotes and affirmations based on the user’s mood or preferences.

## Features
1. **Daily Affirmations**  
   - Display a random affirmation when the user logs in.  
   - Filter affirmations based on mood categories (e.g., happy, stressed).

2. **User Customization**  
   - Allow users to add their own affirmations.  
   - Save favorite affirmations for quick access.

3. **API Integration**  
   - Fetch additional quotes and affirmations from external APIs.

## Tech Stack
- **Backend**: Flask for managing routes and API integration.  
- **Frontend**: HTML, CSS, and JavaScript for a simple UI.  
- **Database**: SQLite for storing user preferences and custom affirmations.  
- **API**: Use a motivational quotes API like ZenQuotes.

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/egeuysall/daily-affirmations.git
   ```

2. Navigate to the project directory:  
   ```bash
   cd daily-affirmations
   ```

3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

4. Start the Flask server:  
   ```bash
   python app.py
   ```

5. Open your browser and go to:  
   ```
   http://localhost:5000
   ```

## Future Enhancements
- Add a scheduler to send affirmations via email or SMS.  
- Enable mood tracking with a graphical interface.  
- Implement a dark mode for better user experience.
