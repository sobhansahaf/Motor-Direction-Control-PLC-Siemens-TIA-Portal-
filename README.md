# Motor-Direction-Control-PLC-Siemens-TIA-Portal-
This project demonstrates a simple **PLC-based motor control system** using two start buttons (Left Rotation and Right Rotation), one stop button, and a single motor.
The logic is designed so that the motor can switch between **left** and **right** rotation with a **5-second delay** between direction changes to ensure safe operation.

---

## 📌 Project Description

The system includes:

* **Left Rotation Start Button**
* **Right Rotation Start Button**
* **Stop Button**
* **Motor**

### 🔧 Operating Logic

1. When the **Left Start** button is pressed:

   * The motor begins rotating **to the left (counter-clockwise)**.

2. When the **Right Start** button is pressed:

   * The motor stops its current motion.
   * After a **5-second delay**, it begins rotating **to the right (clockwise)**.

3. When the **Left Start** button is pressed again during right rotation:

   * The motor stops its current motion.
   * After a **5-second delay**, it begins rotating **to the left** again.

4. Pressing the **Stop Button** immediately stops the motor.

This delay ensures mechanical safety and prevents damage due to sudden direction changes.

---
