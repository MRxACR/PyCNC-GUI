
![Logo](https://github.com/MRxACR/PyCNC-GUI/blob/master/ui/images/Zenbreak%20Electronics.png)

# 🛠️ PyCNC-GUI

A Python-based CNC controller for **Raspberry Pi 4/5** and other ARM Linux boards — now with a **graphical user interface (GUI)**.

This project is a fork and extension of [Nikolay-Kha's PyCNC](https://github.com/Nikolay-Kha/PyCNC), designed for easier setup, GUI-based interaction, and compatibility with Raspberry Pi hardware.

---

## ✨ Features

- 🧠 Pure Python G-code interpreter and CNC motion controller
- 🖥️ **Custom-built GUI** using PyQt6
- 🐧 Updated for **Raspberry Pi (4/5)** and other ARM-based Linux boards
- 🛠️ Uses GPIO pins for stepper control
- 🪛 Easily customizable for various CNC machine configurations

---

## 📦 Installation

```bash
git clone https://github.com/MRxACR/PyCNC-GUI
cd PyCNC-GUI
sudo pip install . --break-system-packages
sudo chmod +x pycnc
sudo apt install python3-pyqt6
```

## 🚀 Usage
🔧 CLI Mode

To run in terminal mode:
```bash
pycnc
# or if you're in the directory:
./pycnc
```

🖥️ GUI Mode

To launch the graphical interface:
```bash
sudo python3 pycnc_ui.py
```
