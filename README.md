---

# Attendance Management System Using Face Recognition

## Summary

This **Attendance Management System** tracks who is present by automatically using facial recognition technology. It is made with Python and uses tools like OpenCV to detect and recognize faces, ensuring accuracy, security, and efficiency. The system is great for schools, workplaces, and events because it provides real-time attendance logging and reporting.

---

## Important Parts

- **Facial Recognition**: Can authenticate users through webcam.
- **Automated Attendance**: Immediately records attendance and stores it in a database.
- **Graphical Reports**: Shows attendance trends with charts.
- **User-Friendly GUI**: An easy interface for smooth interaction.
- **Database Integration**: Maintains safe attendance records and user information.
- **Manual Attendance**: Option Allows fallback for unrecognized faces.
---

## Technologies Used

- **OpenCV**: Detect and recognize faces.

- **NumPy & Pandas**: Data processing and handling.
- **Pillow**: Image resizing and manipulation.
- **Matplotlib**: Graphics data visualization.
- **Dlib**: Facial landmark detection.
- **Tkinter**: Graphical User Interface.
- **MySQL**: A database that keeps records safe.
- **PyCharm**: IDE for development and debugging.
---

## How It Works

1. **Enrollment**: Users register their name, ID, and facial images.

2. **Model Training**: Facial data is applied to train the recognition model.
3. **Attendance Marking**: The system recognizes faces automatically and starts marking attendance on its own.
4. **Manual Ability**: Users can take attendance manually if required.
---

Here’s a formatted and more presentable version of the provided content:

---

## Installation and Setup

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/yourusername/Attendance-Management-System-using-Face-Recognition.git  
   cd Attendance-Management-System-using-Face-Recognition
   ```

2. **Install Dependencies**:  
   ```bash
   pip install -r requirements.txt
   ```

3. **Setup MySQL Database**:  
   - Create a database:  
     ```sql
     CREATE DATABASE attendance_system;
     ```  
   - Update `db_connector.py` with your database credentials.

4. **Run the App**:  
   Execute `AMS_Run.py` to start the system.

---

## Uses

- **Schools**: Automatically tracks student attendance.  
- **Corporate Offices**: Monitors employee attendance efficiently.  
- **Events**: Tracks attendee participation.  
- **Access Control**: Enhances security with face-based entry systems.

---

## Future Improvement

- Mobile app integration.  
- Improved recognition in diverse lighting conditions.  
- Support for multiple camera feeds.

---

## License

Licensed under the MIT License. See `LICENSE` for more details.

---

This format enhances readability while keeping the content intact. Let me know if you'd like further adjustments!
