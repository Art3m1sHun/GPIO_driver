# LED Blink Driver using GPIO (Linux Kernel Module)

This project is a simple Linux kernel module that controls an LED using GPIO and demonstrates basic character driver concepts on embedded Linux systems (e.g., Raspberry Pi or similar boards).

## 📌 Features

- GPIO LED control via Linux Kernel Module
- Simple blink functionality
- Supports GPIO request, direction configuration, and cleanup
- Easy to integrate into Yocto or custom Linux builds
- Useful for learning Linux Device Driver development

---

## 📁 Project Structure

led_blink_driver_GPIO/
│── mgpio.c # Kernel module source code
│── Makefile # Build system for kernel module
│── README.md # Documentation

## ⚙️ Requirements

- Linux kernel headers installed
- Cross compiler (if building for embedded board)
- Raspberry Pi / embedded Linux device with GPIO access
- Root access (insmod/rmmod)

---
# DEMO
https://github.com/user-attachments/assets/9a9a42f2-fca4-4c5f-be26-46c6b4225f9f

