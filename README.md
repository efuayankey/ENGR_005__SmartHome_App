TRANSFERRING DATA TO A WEB APPLICATION

Author: Efua Yankey
Date Written: 27th Sept, 2024
Last updated: 3rd Oct, 2024

Overview:
This project transfers temperature data from an MSP430 microcontroller to a web application via a Windows Forms interface.

Components:
1. MSP430 Program (CSS_lab4_main.c):
   - Reads temperature from internal sensor
   - Sends data via UART

2. Windows Forms App (Form1.cs):
   - Receives data from MSP430
   - Uploads to ThingSpeak

Setup:
1. Program MSP430
2. Connect MSP430 to PC
3. Run Windows Forms app
4. Click 'Start' to begin data transfer

Note: Update COM port and ThingSpeak API Key before use.
