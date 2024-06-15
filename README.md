# PaSCAN - QR Code-Based Attendance Management System with SMS Notification

## Description

PaSCAN is a comprehensive attendance management system designed to simplify and automate the process of marking attendance using QR codes and sending SMS notifications via PhilSMS. Developed during an internship at STI Calbayog, this application efficiently tracks attendance and sends email reports of attendance records. It is built to ensure an easy, user-friendly experience with robust functionality.

## Features

- **QR Code Scanning:** Easily mark attendance using QR codes.
- **Real-Time Attendance Tracking:** Instantly update and track attendance records.
- **SMS Notifications:** Send automated SMS alerts to students via PhilSMS.
- **Email Reports:** Automatically send attendance reports via email in Excel format.
- **User-Friendly Interface:** Clean, intuitive design for easy navigation.
- **Excel Database Integration:** Stores attendance records in an Excel spreadsheet for easy management.

## Prerequisites
Ensure you have the following installed:
- **Python 3.x:** Ensure that you have the latest python installed.   (<a href="https://www.python.org/downloads/" target="_blank">Download the Latest Python Here</a>Download the Latest Python Here</a>)
- **Pip Modules:**
  - colorama==0.4.6
  - numpy==1.26.4
  - opencv-python==4.9.0.80
  - pandas==2.2.1
  - Pillow==10.3.0
  - PyQt5==5.15.10
  - PyQt5-sip==12.13.0
  - python-dateutil==2.9.0.post0
  - pytz==2024.1
  - pyzbar==0.1.9
  - qrcode==7.4.2
  - six==1.16.0
  - XlsxWriter==3.2.0
  - wxPython==4.2.1
  - openpyxl==3.1.4
- **Visual C++ Redistributable Packages:** Ensure that you have the latest Visual C++ Redistributable Packages installed.   (<a href="https://www.techpowerup.com/download/visual-c-redistributable-runtime-package-all-in-one/">Download All-in-one Visual C++ Redistributable Here</a>)


## Installation

To set up the project locally, follow these steps:

1. Clone the repository:

    ```bash
    git clone https://github.com/KENnotcode/PaSCAN-QR-Code-based-Attendance-Management-System-With-SMS-Notification.git
    ```

2. Navigate to the project directory:

    ```bash
    cd STI-Calbayog-intern-Final-project
    ```

3. Install the dependencies:

    ```bash
    npm install or npm i
    ```

4. Start the development server:

    ```bash
    npm start
    ```

## Usage
## Check 'Add Python 3.x to PATH' during installation.
1. <a href="https://github.com/KENnotcode/PaSCAN-QR-Code-based-Attendance-Management-System-With-SMS-Notification/archive/master.zip">Download</a> and extract the zip file.

2. Install requirements (navigate to root directory on command line). Run command:

   ```bash
   pip install -r requirements.txt
   ```
3. Go to 'resources' folder and edit all the JSON files. (You may use the dummy files for testing - check 'dummy-data' directory) (Use <a href="http://jsoneditoronline.org/">this online editor</a> to check formatting errors)

4. From root as present working directory, run the following command:

   ```python
   python PaSCAN QR Code-based Attendance Management System WIth SMS Notification.py
   ```
    Or simple click the start button in Visual Studio Code

5. In the window that opens, click on 'Configure PaSCAN values'. Enter required values. Restart application using the above command.

6. Generate Session Tokens and Attendee Tokens and distribute them as required.

7. Make sure you have a webcam or camera connected and installed on your system. PaSCAN uses primary camera for capturing sessions, make sure its not being used by another application. (Try connecting through different ports if you're using an external webcam)

8. Click START Login Monitor.

## Contributing

We welcome contributions to improve this project! To contribute, please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/YourFeatureName`).
3. Make your changes and commit them (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/YourFeatureName`).
5. Create a pull request.

Please ensure your code adheres to our coding guidelines and is well-documented.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please contact:

- **Project Maintainer**: Kenneth Cubilo, Kringo Carlo Comota
- **Email**: kennethcubilo@gmail.com
- **GitHub**: [KENnotcode](https://github.com/KENnotcode)

---

## NOTE!!
 Make sure to configure all the necessary and required fields in the config.ini file.

Feel free to customize this README file as needed. Add specific details about the technologies used, any additional features, and any other relevant information to provide a comprehensive overview of your project.
