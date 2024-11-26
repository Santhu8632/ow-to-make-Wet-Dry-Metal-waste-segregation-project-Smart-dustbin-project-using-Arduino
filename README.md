# ow-to-make-Wet-Dry-Metal-waste-segregation-project-Smart-dustbin-project-using-Arduino
To implement the circuit for the provided code, follow these steps:

### **Components Needed**
1. Arduino board
2. Stepper motor (with ULN2003 driver module)
3. Servo motor
4. IR sensor
5. Proximity sensor
6. Soil moisture sensor (or potentiometer as a soil simulator)
7. Buzzer
8. Resistors (as needed)
9. Jumper wires
10. Breadboard (optional)

---

### **Circuit Connections**
1. **Stepper Motor:**
   - Connect the stepper motor's four control pins to Arduino pins **8, 9, 10, and 11**.
   - Power the stepper motor through the driver module (5V and GND).

2. **Servo Motor:**
   - Signal pin of the servo motor → Arduino pin **7**.
   - Servo motor's power and GND → Arduino's **5V and GND** pins.

3. **IR Sensor:**
   - VCC pin → Arduino **5V**.
   - GND pin → Arduino **GND**.
   - Signal pin → Arduino pin **5**.

4. **Proximity Sensor:**
   - VCC pin → Arduino **5V**.
   - GND pin → Arduino **GND**.
   - Signal pin → Arduino pin **6** (INPUT_PULLUP).

5. **Buzzer:**
   - Positive terminal → Arduino pin **12**.
   - Negative terminal → Arduino **GND**.

6. **Soil Moisture Sensor (Potentiometer):**
   - Connect the potentiometer's **middle pin** to Arduino **A0** (analog input).
   - Connect the other two pins of the potentiometer to **5V** and **GND**.

---

### **Powering the Circuit**
- Use the Arduino's USB connection or an external power source (if current demand exceeds USB power limits).

### **Diagram Summary**
1. Ensure **shared GND** for all components.
2. Use resistors where necessary (e.g., sensors with pull-up/pull-down resistors).
3. Test each component individually before integrating the entire setup.


