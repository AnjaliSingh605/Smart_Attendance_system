Smart Attendance System 📷📝
This project implements a Smart Attendance System using QR codes and a webcam. It scans QR codes in real-time to mark attendance, ensuring efficient and hassle-free record-keeping.

Features 🌟
📸 Real-time QR Code Scanning: Automatically detects and decodes QR codes from a live webcam feed.
📋 Attendance Management: Tracks attendance and saves it in a text file (attendence.txt).
🔄 Duplicate Entry Prevention: Ensures that each person is marked only once per session.
🕒 Automatic Data Logging: Appends attendance records to a text file for easy access and review.

How It Works 🛠️
A webcam captures the live feed.
QR codes are scanned using the Pyzbar library.
If the QR code data is unique, the name or ID is appended to an attendance file (attendence.txt).
Duplicate entries are ignored, ensuring accurate attendance tracking.

Technologies Used 🧑‍💻
Python: The primary programming language.
OpenCV: For accessing the webcam and displaying the live feed.
Pyzbar: For decoding QR codes.
NumPy: A dependency for image processing.

Prerequisites 📦
Before running the project, make sure you have the following installed:

Python 3.x
Required libraries: Install them using the command below.
bash
Copy code
pip install opencv-python numpy pyzbar

How to Use ▶️
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/smart-attendance.git
cd smart-attendance
Run the script:
bash
Copy code
python smart_attendance.py
Point your webcam at QR codes to scan them.
Press s to stop the program.
The attendance will be saved in attendence.txt.

File Description 📂
smart_attendance.py: Main Python script for the attendance system.
attendence.txt: The text file where attendance data is saved.

Future Improvements 🚀
Add a GUI interface for better user experience.
Store attendance data in a database for enhanced scalability.
Support multiple webcam inputs for larger attendance systems.
Integrate email or SMS notifications for real-time attendance updates.

Contribution 🤝
Contributions are welcome! Feel free to fork the repository and submit pull requests.

