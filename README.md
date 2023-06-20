# alarm-clock

This is a simple alarm clock application built with HTML, CSS, and JavaScript. It allows you to set and clear alarms based on the selected time. When the alarm time matches the current time, a pleasant ringtone is played.


# Features

1. Set and clear alarms easily.
2. Select hour, minute, and AM/PM options from dropdown menus.
3. Displays the current time in a 12-hour format.
4. Plays a ringtone when the alarm time is reached.
5. Validates the selected time to ensure a valid alarm is set.


# Usage

1. Clone or download the repository to your local machine.
2. Open the index.html file in a web browser.
3. Use the dropdown menus to select the desired alarm time.
4. Click the "Set Alarm" button to set the alarm.
5. If you want to clear the alarm, click the "Clear Alarm" button.


# How It Works

The application uses JavaScript to dynamically generate the options for hour, minute, and AM/PM dropdown menus. It then continuously updates and displays the current time on the page. When the alarm time matches the current time, a ringtone is played. The setAlarm() function handles setting and clearing alarms based on user interactions.


# Dependencies

This alarm clock application relies on an external audio file located at ./sound/mixtap.mp3 for the ringtone. Ensure that the audio file is present in the correct directory relative to the HTML file.


# Contributions

Contributions to the project are welcome! If you have any suggestions, improvements, or bug fixes, feel free to create an issue or submit a pull request.
