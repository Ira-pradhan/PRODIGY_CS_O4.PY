# PRODIGY_CS_O4.PY
TASK-04

Create a basic keylogger program that records and logs keystrokes. Focus on logging the keys pressed and saving them to a file. Note: Ethical considerations and permissions are crucial for projects involving keyloggers.

Simple Keylogger:
A keylogger is a program that records keystrokes made on a keyboard. It logs every key press and can save the logged data to a file for analysis. Keyloggers can be used for legitimate purposes like monitoring children's activity or testing software, but they can also be used for unethical purposes, such as stealing passwords or sensitive information. This is why ethical use and getting proper consent are crucial when developing or using such software.

How a Simple Keylogger Works:

1. Monitoring Keyboard Events: The keylogger listens to all keyboard events on a system.

2. Logging Keystrokes: Every time a key is pressed, the keylogger logs the key (or a series of keys).

3. Saving Data: The keystrokes are typically saved into a file for later review.

4. Optional Features: Keyloggers may include features like logging window titles to show where the keys were typed or sending the data over a network.


How It Works:

1. pynput Library: This Python library allows monitoring keyboard and mouse input.

2. on_press Function: Logs each key press. If it's a regular key (a character), it logs the character; for special keys like "Enter" or "Shift," it logs the key name.

3. on_release Function: This stops the keylogger when the "Esc" key is pressed.

4. Logging to File: Each key is logged into a log.txt file, where the keystrokes are saved after every keypress.

Repository Contents:
PRODIGY_CS_04.py : The main python script containing the implementation of the simple keylogger.
README.md : This file providing an overview of the task and the project.
