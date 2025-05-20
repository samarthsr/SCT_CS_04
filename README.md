🔑 Keylogger Script

GitHub README
🔑 Keylogger Script
A Python-based Keylogger that captures keystrokes in real-time and logs them into a file for analysis. This tool is a simple yet effective way to learn about keylogging techniques and the use of event-driven programming in Python.

🚀 Features
Keystroke Logging: Tracks and logs all keystrokes, including special keys like Ctrl, Alt, and Esc.
Real-Time Monitoring: Logs are updated in real-time and saved to a file named keylog.txt.
Special Key Support: Recognizes and handles special keys separately for clarity.
Exit on Demand: Stops the logger when the "Esc" key is pressed.
Lightweight: Minimal dependencies with a focus on efficiency.
📋 How It Works
The program uses Python's pynput library to monitor keyboard events:

Key Press: Logs the character or special key pressed along with a timestamp.
Key Release: Detects the release of keys, allowing the program to respond dynamically.
Logging: Writes all captured information into a keylog.txt file for review.
🛠 Installation & Usage
Prerequisites
Python 3.x installed on your system.
pynput library installed (pip install pynput).
Steps
Clone this repository:
bash
Copy code
git clone https://github.com/samarthsr/SCT_CS_04.git  
cd keylogger  
Run the program:
bash
Copy code
python sct_keylogger.py  
Usage
Launch the script to begin keylogging.
Press the "Esc" key to stop the logger.
Review the captured logs in the keylog.txt file.
👨‍💻 Example
Run the script:
bash
Copy code
python sct_keylogger.py  
Press keys on your keyboard.
View the keylog.txt file for captured output, e.g.:
vbnet
Copy code
2024-12-10 10:30:01,123: Key A pressed  
2024-12-10 10:30:03,456: Special key Key.ctrl pressed  
📚 Concepts Covered
Keyboard Event Handling: Learn to detect and log keystrokes programmatically.
Python Basics: Use libraries and file handling for practical applications.
Logging: Understand real-time data capture and storage in Python.
🤝 Contributing
Contributions are welcome! Feel free to submit pull requests or report issues to enhance this project.

🛡 License
This project is licensed under the MIT License. See the LICENSE file for details.

🌟 Acknowledgments
pynput Documentation for detailed library usage.
Ethical guidelines for responsible development and use of keyloggers.
