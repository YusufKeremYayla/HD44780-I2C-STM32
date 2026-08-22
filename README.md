# STM32 I2C LCD (HD44780) Driver

This library is an I2C-based 16x2 LCD display driver for STM32 microcontrollers, developed using the STM32 HAL (Hardware Abstraction Layer).

## 🚀 Features
* Seamless communication via I2C using the PCF8574 expansion module.
* Standard text printing and character sending operations.
* Cursor control functionalities (Show/Hide).
* Scrolling text feature for strings longer than the display width.

## 🛠️ Technologies Used
* **Hardware:** STM32 Series (Easily portable to other STM32 families), 16x2 Character LCD, I2C Module.
* **Software:** STM32CubeIDE, C Language, STM32 HAL Library.

## 📌 Installation and Usage
1. Copy the `lcd_2x16_drivers.h` and `lcd_2x16_drivers.c` files into your project's `Inc` and `Src` directories, respectively.
2. Enable and configure the I2C peripheral via STM32CubeMX.
3. Make sure to add the `Inc` folder to your compiler's **Include Paths** in the IDE settings before building the project.

<img width="2816" height="1536" alt="Gemini_Generated_Image_ksu6a9ksu6a9ksu6" src="https://github.com/user-attachments/assets/7cbe00d3-a653-4157-9cb9-099240b69d86" />
