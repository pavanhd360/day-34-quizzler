Quizzler App 🧠
A polished, GUI-based quiz application built with Python. This project fetches trivia questions dynamically from an API and features a modern interface to test your knowledge across various topics.

🚀 Features
Dynamic Questions: Fetches real-time trivia questions using the Open Trivia Database API.

Interactive UI: A clean interface built with tkinter, featuring canvas animations for feedback (green for correct, red for incorrect).

Score Tracking: Real-time score updates displayed directly on the interface.

Object-Oriented Design: Modular code structure for easy maintenance and scalability.

🛠️ Built With
Python 3

Tkinter: For the graphical user interface.

Requests Module: To handle API calls and data retrieval.

HTML Entities: To unescape and format API text correctly.

📂 Project Structure
main.py: The entry point of the application.

ui.py: Handles the QuizInterface class and all GUI logic.

quiz_brain.py: Manages the quiz logic, score tracking, and question progression.

question_model.py: Defines the Question class structure.

data.py: Manages the API parameters and initial data fetching.

⚙️ Installation & Usage
Clone the repository:

Bash
git clone https://github.com/pavanhd360/day-34-quizzler.git
Install dependencies:

Bash
pip install requests
Run the application:

Bash
python main.py
