# Automated Attendance System Using Facial Recognition

## Overview
This project implements an automated attendance system using facial recognition technology. It simplifies the process of recording student attendance by leveraging facial recognition, thereby eliminating the need for manual roll calls or sign-ins. The system can generate attendance reports, send notifications to absentees' parents, and email the daily attendance sheet to the concerned faculty or department.

## Features
- **Face Recognition**: Utilizes face recognition technology to mark attendance.
- **Automated Attendance Reports**: Generates and saves attendance reports in Excel format.
- **Email Notifications**: Sends emails to parents of absentees and to faculty with the attendance report attached.
- **Real-Time Monitoring**: Provides real-time attendance tracking and reporting.

## Prerequisites
- Python 3.7+
- OpenCV
- face_recognition library
- xlwt, xlrd, xlutils libraries
- smtplib for sending emails

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/yourusername/automated-attendance-system.git
    cd automated-attendance-system
    ```

2. **Install the required Python packages:**

    ```bash
    pip install -r requirements.txt
    ```

3. **Set up your environment:**

    - Place student images in the `student_images` directory.
    - Ensure you have a `master_dataset.xls` file in the root directory containing student roll numbers, names, phone numbers, and email addresses.

