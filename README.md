# Home-Automation-System-using-ESP32
This project is a simple yet powerful Home Automation System built using an ESP32-WROOM-32 microcontroller and a 4-channel relay module. It allows users to control home appliances (like lights, fans, etc.) remotely over Wi-Fi using a web interface or mobile app.

## 🔧 Features
- ✅ ESP32-WROOM-32 microcontroller
- ✅ Control up to 4 appliances (lights, fans, etc.)
- ✅ Web-based interface hosted on ESP32
- ✅ Uses GPIO 23, 22, 21, and 19 for relay control
- ✅ Real-time switching of appliances
- ✅ Accessible via phone or PC over local Wi-Fi
- ✅ Low-cost solution for smart home automation

---

## 🧰 Tech Stack

| Component      | Used For              |
|----------------|------------------------|
| ESP32-WROOM-32 | Main control unit       |
| Relay Module   | Switching appliances    |
| Arduino IDE    | Programming ESP32       |
| HTML/CSS       | Web interface (optional)|

---

## ⚙️ Circuit Diagram
![Circuit Digram](https://github.com/user-attachments/assets/0674371e-93a2-4eae-add9-fa728e32f502)

ESP32 pins are connected to the relay module as follows:

| Relay Channel | GPIO Pin |
|---------------|-----------|
| Relay 1       | GPIO 23   |
| Relay 2       | GPIO 22   |
| Relay 3       | GPIO 21   |
| Relay 4       | GPIO 19   |

---

## 🚀 Getting Started

### Prerequisites

- Arduino IDE installed  
- ESP32 board package added to Arduino IDE  
- Micro USB cable  
- 5V relay module  
- Wi-Fi network credentials

### Steps

1. Clone this repo:
    ```bash
    git clone https://github.com/your-username/home-automation-esp32.git
    ```
2. Open the `.ino` file in Arduino IDE  
3. Set your **Wi-Fi SSID and Password** in the code  
4. Select **ESP32 Dev Module** from Tools → Board  
5. Upload the code to the ESP32  
6. Connect your ESP32 to power  
7. Open the IP address shown in Serial Monitor on your browser  
8. Control your appliances remotely!
