# ESP32 Potentiometer Project

This is a simple analog input experiment using an ESP32 and a potentiometer. The project reads analog voltage values from the potentiometer and displays them in real-time via the Serial Monitor.

##  What’s Inside

- ESP32 microcontroller setup
- Potentiometer connected to GPIO34
- Live analog-to-digital value display (range: 0–4095)
- Code written in Arduino IDE

## Circuit Setup

I. Place the potentiometer on a breadboard  
II. Connect:
   - Left leg → 3.3V on ESP32  
   - Right leg → GND  
   - Middle pin → GPIO34  
III. Connect ESP32 to your computer via USB  
IV. Upload the Arduino code and monitor readings in Serial Monitor  

## Expected Output

- As you rotate the potentiometer, the Serial Monitor should show values from ~0 to 4095.
- This represents how the analog signal is digitized by the ESP32’s ADC.

## Requirements

- ESP32 board
- Arduino IDE (with ESP32 board package installed)
- USB Cable
- Potentiometer
- Breadboard + Jumper Wires

## Serial Config

- Baud rate: `115200`
- Port: COM port where ESP32 is connected
- Board: ESP32 Dev Module (or match your specific ESP32 type)
