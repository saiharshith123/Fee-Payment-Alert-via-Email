# Fee-Payment-Alert-via-Email

## Overview
Fee-Payment-Alert-via-Email is a console-based Python project that helps administrators send fee payment reminders via email. It includes OTP-based authentication for secure access and allows sending customized notifications to users with pending or cleared fees.

## Features
- OTP-based authentication for admin login.
- Send fee pending reminders to students via email.
- Send fee clearance confirmation emails.
- Ability to edit user fee status.

## Prerequisites
- Python 3.x
- Gmail SMTP server access
- Required Python libraries:
  - `smtplib`
  - `email`
  - `random`

## Installation
1. Clone this repository:
   git clone https://github.com/yourusername/Fee-Payment-Alert-via-Email.git
2. Navigate to the project folder:
   cd Fee-Payment-Alert-via-Email
4. Install necessary dependencies (if required):
   pip install smtplib email

## Configuration
Update the username and password fields in the script with your Gmail credentials (ensure you use an App Password instead of your actual password for security).

## Usage
1. Run the script:
  -  python main.py
2. Enter the admin username (admin).
3. An OTP will be sent to the registered admin email.
4. Enter the OTP to proceed.
5. Choose an option from the menu:
  -  Edit fee status.
  -  Send emails to users with pending fees.
  -  Send emails to users with cleared fees.
  -  Exit the application.

## Security Note
Avoid hardcoding credentials in the script. Use environment variables or a configuration file instead.
Ensure that you enable "Less Secure Apps" access or use an App Password for sending emails via Gmail.

## License
This project is open-source and available under the MIT License.

