# IDAI101-2505445--PYTHON-SA
MedTracker app ( Python, VS Code, Streamlit )

Adhera — Your Daily Health Companion

Summative Assessment Report
By: Snigdha Reddy Guduru
Subject: Python Programming

Introduction

For my Python Summative Assessment, I developed a web-based application called Adhera — Your Daily Health Companion.
It is built with Python and Streamlit and designed to help users track their daily medications. The app allows users to add their medications, mark whether they have been taken or missed, and view their progress over time.

The main reason I chose this idea was that I wanted to create something meaningful and practical. Many people, including elders and students, often forget their daily medications. I wanted to build a simple, accessible, and visually clean application that could help them stay consistent with their medication routine.

Research About the App

Before creating the app, I explored a few existing medicine reminder and health tracking applications. Most of them included features such as scheduling doses, tracking adherence, and displaying progress. I decided to design a simpler version that focuses on usability, basic reminders, and data visualization.

Adhera uses the Streamlit framework because it allows developers to create interactive web apps entirely in Python. The main libraries I used are pandas for data handling, matplotlib for charting, and Pillow (PIL) for generating a simple logo.

Below is a summary of the main features and how they work:

Medicine Management:
Users can add, delete, or import multiple medicines. Each medicine includes a name, scheduled time, and optional notes.

User Login:
Each user gets a separate JSON file (e.g., adhera_snigdha.json) that stores their data. This ensures that multiple users can use the app without overwriting each other’s records.

Daily Tracking:
The app lets users mark their medicines as taken or missed, and it automatically saves the records with timestamps.

Weekly Adherence Calculation:
Adhera calculates the percentage of medicines taken over the past week and displays it using both a metric and a progress bar.

Visual Analytics (Chart):
The app shows a 14-day adherence chart, allowing users to see how consistent they’ve been.

Next Dose Countdown:
Adhera identifies the next scheduled dose and displays how long is left until it’s due.

Missed Dose Notifications:
If the user misses a dose, the app highlights it and allows them to simulate sending a reminder.

Encouragement Messages:
The app displays short motivational messages based on the user’s adherence percentage.

Dark Mode UI:
All text and accents are white against a dark background, creating a clean and professional look.

Through this project, I understood how Python can be used not only for backend logic but also for front-end design and real-time interactivity.

Reflection

Developing Adhera was a challenging but rewarding experience. I learned how to combine different Python concepts — from data handling and file management to visualization and web development.

Initially, I struggled with issues related to Streamlit’s session state and how to make data persist after the app was closed. Solving those problems helped me gain a better understanding of how real applications store and retrieve data.

I also faced errors while implementing features like the chart, CSV import, and dark theme. Debugging those issues taught me patience and the importance of testing every small function carefully.

My favorite part was designing the interface and ensuring that it looked simple and easy to use. I also learned how adding small touches, like an encouragement message or a visual chart, can make an app feel more personal.

If I had more time, I would add actual reminder notifications through email or phone alerts to make it more realistic. I would also try hosting the app online so that others could use it easily.

Overall, this project helped me see Python from a more practical angle. I realized that coding can be used to build tools that genuinely solve small, real-world problems. Adhera reflects not only my technical learning but also my creativity and effort to make something useful.

Conclusion:
Working on Adhera taught me that good software is not just about code — it’s about making life a little easier for the people who use it. This project helped me combine logic, design, and empathy into one complete product, and I am proud of how it turned out.

<img width="1440" height="900" alt="Screenshot 2025-11-08 at 12 29 17 PM" src="https://github.com/user-attachments/assets/c28a8324-d88d-4736-816d-1b6ae1debe93" />

<img width="1440" height="900" alt="Screenshot 2025-11-08 at 12 29 06 PM" src="https://github.com/user-attachments/assets/8ba626ab-eb8b-4d3f-8b39-1fa50528c98a" />

<img width="1440" height="900" alt="Screenshot 2025-11-08 at 12 28 49 PM" src="https://github.com/user-attachments/assets/53d5fd75-9ff6-43a4-a489-7b3fd488eaf2" />

<img width="1440" height="900" alt="Screenshot 2025-11-08 at 12 28 37 PM" src="https://github.com/user-attachments/assets/50674452-4581-49bb-8a68-728ec9867288" />


