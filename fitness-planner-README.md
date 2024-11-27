
# Personal Fitness Planner

A web application to log workouts, track progress, and set fitness goals.

## Features
1. **Workout Logging**  
   - Add and track daily workouts (type, duration, calories burned).  
   - Categorize workouts by type (e.g., cardio, strength, yoga).

2. **Progress Tracker**  
   - Visualize progress with charts (e.g., weekly stats).  
   - Track personal records for exercises.

3. **Fitness Goals**  
   - Set and manage fitness goals (e.g., weight loss, endurance improvement).  
   - Track goal completion over time.

## Tech Stack
- **Backend**: Flask for managing workout data and logic.  
- **Frontend**: HTML, CSS, and JavaScript for an interactive UI.  
- **Database**: SQLite for storing workout logs and goals.  
- **API**: Integrate a calorie-burning calculator API.

## How to Run
1. Clone the repository:  
   ```bash
   git clone https://github.com/egeuysall/fitness-planner.git
   ```

2. Navigate to the project directory:  
   ```bash
   cd fitness-planner
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
- Add social features (e.g., share progress with friends).  
- Integrate wearable device data (e.g., Fitbit or Apple Watch).  
- Include meal planning and nutrition tracking.
