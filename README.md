# LED Blinking with Arduino

## 🚀 Overview
This simple Arduino project demonstrates how to blink an LED connected to pin 12. The LED turns **ON for 2 seconds** and then **OFF for 2 seconds**, repeating indefinitely.

## 🛠 Components Required
- 🟢 Arduino Board (Uno, Mega, Nano, etc.)
- 💡 LED
- 🔌 Resistor (220Ω)
- 🛠 Connecting Wires

## 🔌 Circuit Diagram
1. Connect the **positive leg (anode)** of the LED to **pin 12** on the Arduino.
2. Connect the **negative leg (cathode)** of the LED to a **220Ω resistor**, then to **GND** on the Arduino.

## 📜 Code Explanation
```cpp
// Set pin 12 as output
void setup() {
  pinMode(12, OUTPUT);
}

// Loop to turn the LED on and off
void loop() {
  digitalWrite(12, HIGH); // Turn LED ON
  delay(2000);            // Wait for 2 seconds
  digitalWrite(12, LOW);  // Turn LED OFF
  delay(2000);            // Wait for 2 seconds
}
