# 🟦 Port Management System — STM32F103C6

This project implements a **digital port management system** using the STM32F103C6 microcontroller. It provides full control and monitoring of GPIO ports, allowing input reading, output toggling, port initialization, and real-time status visualization.

Useful for learning embedded development, testing peripherals, or building automation/control systems.

---

## 🚀 Features
- ✔ Based on **STM32F103C6 (Blue Pill)**
- ✔ Complete **GPIO port initialization** (input, output, pull-up, pull-down)
- ✔ Digital input monitoring
- ✔ Digital output control (set, reset, toggle)
- ✔ Debouncing logic (optional)
- ✔ Busy indicators or LED feedback

---

## 🧩 Hardware Overview

### **Microcontroller**
- STM32F103C6
- ARM Cortex-M3 @ 72 MHz  
- 64 KB Flash, 20 KB RAM  

### **Clock Configuration**
- HSE: 8 MHz external crystal  
- SYSCLK: 72 MHz  
- AHB: 72 MHz  
- APB1: 36 MHz  
- APB2: 72 MHz  
---

## 🛠 Development Tools
- **STM32CubeIDE**
- **STM32CubeMX**
- **Git & GitHub**
- **Proteus / Hardware testing**

---

## 📂 Project Structure
/Core
/Inc → Header files
/Src → Main application source files
/Drivers → HAL drivers provided by STM32CubeMX
STM32F103C6.ioc → CubeMX project file
README.md → Project description


---

## 🔧 How to Use

### 1. Clone the Repository
```bash
git clone https://github.com/JavierRiv0826/STM32-port-management.git
```

### 2. Open in STM32CubeIDE
- File → Open Projects from File System  
- Select the project folder

### 3. Build the Project
Press **Ctrl + B**  
or  
Project → Build Project

### 4. Flash the Microcontroller
- Connect ST-Link or USB-to-Serial (bootloader mode)
- Press **Debug** or **Run*
  
---


## 👤 Author
**Javier Rivera**  
GitHub: *JavierRiv0826*

