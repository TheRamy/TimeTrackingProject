
# Pomodoro Tracker App

  
This is a simple Pomodoro Tracker App that allows you to track your productivity sessions, store them in a JSON database file, and send a summary of your finished tasks to your email.
  

## Requirements

  

 1. Python 3.6 or higher
 2. pip package installer
 3. smtplib library for sending emails
 4. PyQt5 5.15.7

## Installation

  

Clone or download the repository to your local machine.
Navigate to the project directory in your terminal / command prompt.
Install the required packages by running the following command:


    pip install -r requirements.txt

## Usage

  

Run the main.py file by typing the following command in your terminal:

    python3 main.py

The app will ask you to enter the project, subject and task name, it will then start the pomodoro timer with short and long breaks as per the technique which was developed in the late 1980s by then-university student Francesco Cirillo. This technique helps the ones who are struggling to focus on their studies and complete assignments. 

After 4 pomodoros, the app will mark the task as complete by default. The app will then store the task information in a JSON database file.

You can also email yourself a summary of what you've been working on.

## Contributing

  

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

  

## License

  This project is licensed under the MIT License.
