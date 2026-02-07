# Smart Medicine Reminder System using LPC2148(Proteus)

## Project Description
🩺 DoseGuardian – Smart Medication Reminder System
DoseGuardian is a microcontroller-based intelligent medicine reminder designed to ensure patients take their medications on schedule. It is particularly helpful for elderly people and those undergoing long-term treatments who may forget or skip doses.
The system integrates a Real-Time Clock (RTC), LCD display, keypad interface, and audio-visual alerts to deliver a dependable and easy-to-use medication reminder solution.

## 🧠Key Features

  ⏰ Real-Time Clock (RTC) based time tracking

  📟 16×2 LCD display for messages

  🔢 4×4 Matrix Keypad for user input

  🔔 Buzzer alert at medicine time

  💡 LED warning and status indication

  ✅ Medicine taken confirmation

  ❌ Missed medicine detection

  🧩 Menu-driven interface

## 🛠️ Hardware Components (Proteus)

  🔹LPC2148 ARM7 Microcontroller

  🔹16×2 Alphanumeric LCD

  🔹4×4 Matrix Keypad

  🔹Active Buzzer

  🔹Red LED

  🔹Push Buttons

  🔹1kΩ Resistors

 🔹3.3V / 5V Power Supply

## 🧪 Software Tools Used

  🖥️ Proteus Design Suite (Simulation)

  🧑‍💻 Keil µVision (Embedded C)

  🗂️ GitHub (Version Control)

## 🖼️ Proteus Simulation Screens & Explanation

## 1️⃣ LCD Interface & Pin Test

  🔹Displays test characters on LCD

  🔹Verifies D0–D7 data line connections

  🔹Confirms LCD works in 8-bit mode ✅

## 2️⃣ RTC Date & Time Display
![image alt](https://github.com/naveenpydi3029/DOSE-GUARDIAN/blob/41b5aa3f6266d67279a9d4fbef4c30de23e4edbe/Screenshots/RTC_TIME.png)




  🔹 Shows current time in HH:MM:SS format

  🔹Displays date and day (DD/MM/YYYY)

  🔹RTC runs continuously ⏳

## 3️⃣ Main Menu Screen
![image alt](https://github.com/naveenpydi3029/DOSE-GUARDIAN/blob/4660064bb025adf407275396f000897e1265050e/Screenshots/MENU.png)



  🔹Menu navigation using keypad

  🔹User-friendly interface 🧭

## 4️⃣ Time & Medicine Setup Menu
![image alt](https://github.com/naveenpydi3029/DOSE-GUARDIAN/blob/802871054356a92d93ef35a6f519ca231c8c2040/Screenshots/RTC_EDIT.png)





  🔹Set hours, minutes, seconds

  🔹Configure medicine reminder time ⏰

## 5️⃣ Medicine Time Alert
![image alt](https://github.com/naveenpydi3029/DOSE-GUARDIAN/blob/0122acdbafe75ab6a1b718154b1277b9e15db26e/Screenshots/MEDICINE_TIME.png)



  🔹LCD shows MEDICINE TIME

  🔹Buzzer turns ON 🔔

  🔹LED glows for attention 💡

## 6️⃣ Take Medicine Alert
![image alt](https://github.com/naveenpydi3029/DOSE-GUARDIAN/blob/03357e10a67e3c8c7c923f5cd91c6df77543b8b2/Screenshots/REMINDER.png)




  🔹LCD displays REMAINDER! TIME FOR DOSE

  🔹System waits for user confirmation

  🔹Switch press confirms intake ✅

## 7️⃣ Medicine Taken Confirmation
![image alt](https://github.com/naveenpydi3029/DOSE-GUARDIAN/blob/641bdc5c6d8b7a5822c01bc55092573c0e90bb9c/Screenshots/MED_TAKEN.png)



  🔹LCD shows MEDICINE TAKEN

  🔹Buzzer turns OFF 🔕

  🔹LED turns OFF

  🔹Successful confirmation 🎉

## 8️⃣ Failure to Take Medicine
![image alt](https://github.com/naveenpydi3029/DOSE-GUARDIAN/blob/d2579171a3f6442e9522397fb5f983f4417ca4f4/Screenshots/ALERT.png)


  🔹Triggered if switch is not pressed ❌

  🔹LCD shows ALERT! DOSE MISSED

  🔹Warning LED remains ON 🚨

## 🔁 Working Flow

  1. Power ON the system 🔌

  2. RTC starts time counting ⏱️

  3. User sets medicine time via keypad

  4. RTC compares with medicine time

  5. Alert triggers at match

  6. User confirms medicine intake

  7. Status is displayed on LCD

## 🎯 Applications

  👴 Elderly care systems

  🏥 Hospital medicine reminders

  🏠 Home healthcare automation

  🎓 Embedded systems learning

## 🚀 Future Enhancements

  📲 GSM/SMS alerts to caretaker

  💾 EEPROM data storage

  📱 Mobile app integration

  🔋 Battery backup support

## 👨‍💻 Author

### PYDI NAVEEN
  🎓 ECE Student | Embedded Systems Enthusiast

  💡 Interested in ARM, Embedded C & IoT

## ⭐ Support
If you like this project:

  ⭐ Star this repository

  🍴 Fork it

  🛠️ Contribute improvements

Happy Coding! 🚀
