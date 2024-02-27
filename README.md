# Face Based Attendance System using Python and OpenCV

Welcome to the Face Based Attendance System repository! This project utilizes Python and OpenCV for facial recognition and attendance management.

## Steps to Follow

1. **Download or Clone Repository**: Download or clone the repository to your local device.

2. **Install Requirements**: Open your command prompt and navigate to the project directory. Type `pip install -r requirements.txt` to install the required packages for the project.

3. **Create TrainingImage Folder**: Create a folder named `TrainingImage` within the project directory. This folder will store images used for training the facial recognition model.

4. **Update File Paths**: Open the `attendance.py` and `automaticAttendance.py` files and update all file paths according to your system configuration.

5. **Run the Program**: Execute the `attendance.py` file to start the program.

## Project Flow & Explanation

1. **Register New Student**: Click on the "Register New Student" button to add a new student to the system. Enter the student's ID and name, then click on the "Take Image" button. The system will capture multiple images of the student's face and store them in the `TrainingImage` folder.

2. **Train Image**: After capturing images for all students, click on the "Train Image" button. This will train the facial recognition model using the images stored in the `TrainingImage` folder.

3. **Automatic Attendance**: Enter the subject name and click on the "Automatic Attendance" button. The system will use the trained model to recognize faces and mark attendance automatically. Attendance records will be stored in CSV files, with each subject having its own file.

4. **View Attendance**: Click on the "View Attendance" button to view attendance records. Attendance data will be displayed in a tabular format.
   ![IMG_20240126_160525](https://github.com/RNNivash/Smart_attendance_system/assets/90308206/b9f10b73-50d0-4c6e-873f-a37824de44b4)



## Contact Information

For any questions, feedback, or support, please feel free to reach out to the project maintainer:

- **Maintainer**: Nivash R N
- **LinkedIn**: [Nivash R N](https://www.linkedin.com/in/nivash-r-n-sns/)
- **GitHub**: [Nivash R N](https://github.com/RNNivash)

Thank you for your interest in the Face Based Attendance System project! We hope it proves to be useful for your needs.
