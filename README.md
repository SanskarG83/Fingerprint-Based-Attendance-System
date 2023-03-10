# Fingerprint-Based-Attendance-System
The Attendance Management Application is a mobile application built using the Flutter framework. This application allows users to mark their attendance for a specific class or event, view their attendance history, and view attendance statistics for a class or event.

# Overview

The application has two ways to login, one for students and one for educators. The student login allows students to mark their attendance for a specific class or event and view their attendance history. This application allows students to mark their attendance for a specific class or event based on their proximity to the educator's GPS location and when the educator has started the attendance. The educator login allows educators to make new classes, view attendance statistics for a class or event and start/stop the attendance.

Overall, this application is a useful tool for students, teachers, or anyone else who needs to keep track of attendance for a class or event. The separate login for students and educators ensures that the users have access to only the relevant information and functionality, making it easy to use, and provides real-time information about attendance statistics. The geolocation feature ensures that the attendance is marked only when the student is physically present in the class.

# Getting started

1. Clone the repository to your local machine :
   git clone https://github.com/Om-Gujarathi/Attendance-System-Flutter.git

2. Navigate to the project directory :
   cd Attendance-System-Flutter

3. Install the necessary dependencies :
   flutter pub get

4. Run the app on an emulator or connected device :
   flutter run
   
# Demo:

1) User (Student) Login Interface:

https://user-images.githubusercontent.com/100311018/215962223-09738a19-2bd2-4aa7-af66-66f1fffa5735.mp4

2) Admin (Teacher) Login Interface:

https://user-images.githubusercontent.com/100311018/215962537-fb82ee03-28cc-42d9-a09b-d7619c41233b.mp4


# How it's made:
- Flutter - The mobile app development framework used
- Node.js - The JavaScript runtime used for the server-side logic and REST API's
- MongoDB - The NoSQL database used for storing the attendance data
- Render - The platform used for hosting the Node.js server and REST API's

The Flutter framework was used to build the front-end of the application and provide a seamless user experience. The Node.js runtime was used for the server-side logic to handle the communication with the database and provide a secure and efficient way to handle the attendance data. We have also written RESTful APIs in Node.js that handle the communication between the mobile app and the server. These REST APIs were hosted on Render, a platform that provides easy and convenient hosting solutions for Node.js applications. The MongoDB database was used to store the attendance data and provide a flexible and scalable solution for data management.

