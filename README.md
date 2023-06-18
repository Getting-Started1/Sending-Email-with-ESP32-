ESP32 Send Emails using an SMTP Server: HTML, Text, and Attachments (Arduino IDE).
SMTP Servers.
SMTP means Simple Mail Transfer Protocol and it is an internet standard for email transmission. To send emails using an ESP32, you need to connect it to an SMTP Server.

ESP Mail Client Library.
To send emails with the ESP32, we’ll use the ESP-Mail_Client library. This library allows the ESP32 to send and receive emails with or without attachments via SMTP and IMAP servers.

Sender Email (New Account)
Use a Newley created Gmail account 

Create an App Password.
You need to create an app password so that the ESP32 is able to send emails using your Gmail account. An App Pasword is a 16-digit passcode that gives a less secure app or device permission to access your Google account.
An app password can only be used with account that have 2-step verification turned on.


Gmail SMTP Server Setting.
If you are using gmail these are the SMTP Server details:
•	SMTP Server: smtp.gmail.com
•	SMTP username: Complete Gmail address.
•	SMTP password: Your Gmail password.
•	SMTP port (TLS): 587
•	SMTP port (SSL): 465
•	SMTP TLS/SSL required: yes.
