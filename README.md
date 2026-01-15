# helloworld.py
🐍 TASK 1: Python Environment Setup & First Script
📌 Objective

The objective of this task is to set up a Python development environment, understand basic project structure, and write a simple Python script using variables, user input, and comments. This task helps build a strong foundation for Python programming and real-world development practices.

🛠 Tools & Technologies

Python 3.x

Visual Studio Code (VS Code)

Python Extension for VS Code

Terminal / Command Prompt

📂 Project Structure
python_basics_project/
│
├── hello_world.py
└── README.md

⚙️ Setup Instructions
1️⃣ Install Python

Download Python from the official website:
https://www.python.org/downloads/

During installation, select “Add Python to PATH”.

Verify installation:

python --version

2️⃣ Install VS Code & Python Extension

Download VS Code:
https://code.visualstudio.com/

Open VS Code → Extensions → Install Python (Microsoft).

3️⃣ Create Project Folder

Create a new folder for the project.

Open the folder in VS Code to simulate a real project environment.

🧾 Task Description

Create a Python file named hello_world.py.

Use variables to store values.

Print name, internship role, and today’s date.

Accept user input for name and role.

Add comments to explain the code.

Run the program using terminal.

🧑‍💻 Python Script (hello_world.py)
# Import datetime module to get today's date
import datetime

# Take user input for name
name = input("Enter your name: ")

# Take user input for internship role
role = input("Enter your internship role: ")

# Get today's date
today_date = datetime.date.today()

# Display the output
print("\n--- Intern Details ---")
print("Name:", name)
print("Internship Role:", role)
print("Today's Date:", today_date)

▶️ How to Run the Program

Open terminal in VS Code

Navigate to project folder

Run the script:

python hello_world.py

✅ Expected Output
Enter your name: Vasu
Enter your internship role: Python Intern

--- Intern Details ---
Name: Vasu
Internship Role: Python Intern
Today's Date: 2026-01-15

🎯 Learning Outcomes

Installed and verified Python environment

Used VS Code for Python development

Understood basic project structure

Learned variables, input/output, and comments

Ran Python scripts using terminal.
📌 Conclusion

This task provides hands-on experience with Python setup and basic scripting. It establishes a solid base for future Python concepts and internship-level projects.
