# STM32F103C8T6-Real-Time-Clock-RTC-Watch-with-SSD1306-OLED-Display
STM32F103C8T6 RTC watch with SSD1306 OLED display. This project uses STM32CubeMX and Keil uVision to configure and program the RTC to display time and date on an OLED via I2C. It features the STM32's internal RTC and SSD1306 OLED, utilizing the HAL library for simple and efficient code.
This repository contains the complete project files and source code for building a real-time clock (RTC) watch using the STM32F103C8T6 microcontroller and an SSD1306 OLED display. The project is developed using STM32CubeMX for project configuration and Keil uVision for coding and programming.

Project Overview:
This project showcases how to create a simple RTC watch that displays the current time and date on an SSD1306 OLED display. The display is connected to the STM32F103C8T6 microcontroller via the I2C protocol, ensuring a smooth and efficient data transfer between the two components. The internal RTC of the STM32 is used to maintain accurate timekeeping, even during power resets.

Key Features:
Real-Time Clock (RTC): The internal RTC of the STM32F103C8T6 is utilized to keep track of time without requiring an external module.
OLED Display (SSD1306): The time and date are shown on an SSD1306 OLED display, featuring a clear and crisp 128x64 pixel resolution.
HAL Library: The project leverages STM32’s HAL (Hardware Abstraction Layer) library to ensure the code is simple, readable, and easy to modify.
Tools & Components:
Microcontroller: STM32F103C8T6
Display: SSD1306 OLED (I2C interface)
Development Tools: STM32CubeMX, Keil uVision
Programming Language: C
How to Use:
Clone this repository to your local environment.
Open the project in Keil uVision.
Flash the code to your STM32F103C8T6 microcontroller.
Connect the SSD1306 OLED display as per the provided schematic.
Feel free to explore, modify, and contribute to this project!

