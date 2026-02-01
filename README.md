# Sleep_quality_predictor_cybernaut_ml_miniproject2
💤 Sleep Quality Predictor

A Python-based Machine Learning application that predicts a user’s sleep quality based on lifestyle and sleep-related factors.
The system automatically calculates sleep duration, handles flexible time inputs (AM/PM), provides personalized suggestions, and visualizes sleep trends using graphs.

📌 Project Overview

Sleep quality plays a vital role in physical and mental well-being. This project analyzes daily habits such as sleep schedule, caffeine intake, stress level, and screen time to predict overall sleep quality.

Using a Random Forest Classifier, the application classifies sleep quality into:

🟢 Good

🟡 Average

🔴 Poor

The project is built as a CLI-based application, making it lightweight, easy to run, and ideal for learning and demonstration purposes.

🎯 Objectives

Predict sleep quality using machine learning

Automatically calculate sleep duration from bedtime and wake-up time

Handle real-world user inputs (AM/PM, HH, HH:MM)

Provide actionable sleep improvement suggestions

Track sleep history

Visualize sleep duration and quality trends over time

Build a submission-ready ML mini project

✨ Features

✅ Machine Learning-based sleep quality prediction
✅ Automatic sleep duration calculation
✅ AM/PM and 24-hour time format support
✅ Robust input validation (no crashes)
✅ Personalized sleep improvement suggestions
✅ Sleep history tracking
✅ Graphical visualization of sleep trends
✅ Modular, readable, and extendable code

🛠️ Technology Stack

Programming Language: Python 3

Libraries Used:

NumPy – numerical computations

Pandas – data processing and dataframes

Scikit-learn – machine learning (Random Forest)

Matplotlib – sleep trend visualization

Interface: Command Line Interface (CLI)

📂 Project Structure
sleep-quality-predictor/
│
├── sleep_quality_predictor.py   # Main application file
├── README.md                    # Project documentation
└── requirements.txt             # Required Python libraries

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/sleep-quality-predictor.git
cd sleep-quality-predictor

2️⃣ Install Dependencies
pip install -r requirements.txt


requirements.txt

numpy
pandas
scikit-learn
matplotlib

▶️ How to Run
python sleep_quality_predictor.py

🧪 Sample Input
Bedtime (e.g., 10 pm, 22, 22:30): 10 pm
Wake-up Time (e.g., 6 am, 6, 06:30): 6 am
Caffeine Intake: none
Exercise Duration (minutes): 30
Screen Time Before Bed (minutes): 45
Stress Level (1-10): 4
Mood Before Sleep: happy
Sleep Interruptions? (0 = No, 1 = Yes): 0

🕒 Auto-calculated Output
Auto-calculated Sleep Duration: 8.0 hours
Predicted Sleep Quality: Good

📊 Sleep Graph

The application generates a line graph showing:

Sleep Duration (hours) over days

Sleep Quality Level (Poor → Average → Good)

This helps users visually understand their sleep patterns over time.

🧠 Machine Learning Approach

Model Used: Random Forest Classifier

Dataset: Synthetic dataset generated programmatically

Features Used:

Sleep duration

Bedtime & wake-up time

Caffeine intake

Exercise duration

Screen time

Stress level

Mood before sleep

Sleep interruptions

Target Variable: Sleep Quality (Good / Average / Poor)

📈 Workflow

Generate and preprocess sleep dataset

Encode categorical variables

Train Random Forest model

Accept user input

Auto-calculate sleep duration

Predict sleep quality

Store results in history

Display suggestions

Visualize trends using graphs

📊 Use Cases

Personal sleep monitoring

Health-awareness projects

Machine learning demonstrations

Academic mini / final year projects

Internship portfolio projects

🚧 Limitations

Uses synthetic data (not real medical data)

No persistent database storage

CLI-based interface only

Predictions are not medical diagnoses

🔮 Future Enhancements

Web interface using Streamlit or Flask

Mobile application integration

Database or cloud storage

Integration with wearable devices

Advanced analytics and recommendations

Export reports as PDF/Excel

👩‍💻 Author

Dharshini V
Individual Project
Organisation: Cybernaut

📜 Disclaimer

This project is intended for educational and demonstration purposes only.
It is not a medical diagnostic tool.

⭐ Acknowledgements

Scikit-learn documentation

Python open-source community

Academic mentors and peers
