Project Overview
The Interactive MCQ Quiz System is a Python-based application designed for dynamically generating multiple-choice quizzes from a dataset. It allows users to choose a topic, answer questions interactively, and track their performance on a global leaderboard.

This project leverages IPython Widgets for an interactive user interface, making it ideal for educational purposes, assessments, or fun knowledge-based quizzes.

Features
Dynamic MCQ Generation:

Automatically generates up to 10 random questions for the selected topic.
Options include 1 correct answer and 3 distractors shuffled for every question.
Interactive User Interface:

Simple and intuitive interface built using IPython Widgets for seamless interaction.
Dropdown-based answer selection for each question.
Leaderboard:

Tracks user scores across sessions.
Displays the highest scores and all attempts for each user.
Multiple Topics:

Users can select from various topics (e.g., Python, AI, Data Science, Web Development, etc.).
The dataset is easily customizable for adding new topics and questions.
Reusable Codebase:

Modular functions for MCQ generation, answer evaluation, and leaderboard management.
Can be adapted for different use cases with minimal changes.
How It Works
Dataset:

The project uses a CSV file (Expanded_Quiz_Topics.csv) containing questions, answers, and associated topics.
The dataset can be extended with more topics or questions.
Quiz Workflow:

User enters their username and selects a topic.
The system generates 10 random multiple-choice questions for the topic.
After answering, the user submits their responses to see their score and the updated leaderboard.
Leaderboard:

Tracks and ranks users based on their performance.
Displays the highest scores along with all attempts for each user.
Tech Stack
Programming Language: Python
Interactive Widgets: IPython Widgets
Libraries Used:
pandas: For handling the dataset.
ipywidgets: For creating the interactive quiz interface.
random: For random question generation.
Getting Started
Prerequisites
Python 3.x installed on your system.
Jupyter Notebook or Google Colab for running the application.
Required Python libraries:
bash
Copy code
pip install pandas ipywidgets
Setup
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/interactive-mcq-quiz.git
Navigate to the project directory:
bash
Copy code
cd interactive-mcq-quiz
Ensure the dataset (Expanded_Quiz_Topics.csv) is available in the working directory.
Open the project in Jupyter Notebook or Google Colab and run the Python script.
How to Use
Upload the Expanded_Quiz_Topics.csv dataset or use the default one provided.
Run the script in Jupyter Notebook or Colab.
Enter your username and select a topic to start the quiz.
Answer the 10 questions interactively using dropdowns.
Submit your answers to see your score and the updated leaderboard.
Demo
Below is an example interaction:

Input:

Username: Alice
Topic: Python
Output:

markdown
Copy code
Question 1: What is the result of `len('Hello World!')`?
  1. 12
  2. float
  3. None
  4. Tuple

Question 2: Which module is commonly used for mathematical operations in Python?
  1. pandas
  2. numpy
  3. math
  4. itertools
...
Leaderboard:

java
Copy code
Leaderboard:
Alice: Highest Score = 8, All Scores = [8]
Bob: Highest Score = 10, All Scores = [10, 9]
Customization
Extend the Expanded_Quiz_Topics.csv dataset with new topics and questions.
Customize the UI by adding more widgets or modifying styles.
Contributing
Contributions are welcome! If you'd like to add features, improve the UI, or expand the dataset, please feel free to fork the repository and submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
IPython Widgets for enabling interactive quizzes.
Python community for providing extensive libraries and tools.
