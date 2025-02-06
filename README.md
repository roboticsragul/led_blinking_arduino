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

## 📜 Code
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
```
## 📜 Code Explanation
- `pinMode(12, OUTPUT);` → Sets pin **12** as an output.
- `digitalWrite(12, HIGH);` → Turns the LED **ON**.
- `delay(2000);` → Waits for **2 seconds**.
- `digitalWrite(12, LOW);` → Turns the LED **OFF**.
- `delay(2000);` → Waits for **2 seconds** before repeating.

## 🔧 How to Upload Code
1. Open **Arduino IDE**.
2. Copy and paste the above code.
3. Select the correct **Board & Port**.
4. Click the **Upload** button.

## 🎯 Output
The LED will **blink continuously**, staying **ON for 2 seconds** and **OFF for 2 seconds**.

## 📌 Author
👤 **Robotics Ragul**  
🔗 GitHub: [github.com/your-roboticsragul](https://github.com/roboticsragul)  
