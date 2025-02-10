**# Bluetooth-Controlled Car using Arduino Uno**

## **Overview**
This project is a **Bluetooth-controlled car** that utilizes an **Arduino Uno**, four **DC motors**, **wheels**, a **Bluetooth module**, a **motor driver**, and various **male-female jumper wires**. The car can be controlled remotely via a smartphone application using Bluetooth connectivity.

## **Features**
- Wireless control using a **Bluetooth module (HC-05/HC-06)**.
- Movement in **all directions (forward, backward, left, right, and stop)**.
- Controlled via **an Android smartphone app**.
- **Efficient motor control** using an **L298N motor driver module**.
- Simple wiring with **male-to-female jumper wires**.

## **Components Required**
- **Arduino Uno**
- **HC-05/HC-06 Bluetooth Module**
- **L298N Motor Driver Module**
- **4 x DC Motors**
- **4 x Wheels**
- **12V Battery / Power Source**
- **Jumper Wires (Male-Female)**
- **Chassis (optional)**

## **Setup Instructions**
1. **Assemble the hardware:** Connect **motors, Bluetooth module, and motor driver** to the Arduino Uno.
2. **Upload the code** to the **Arduino Uno** using the **Arduino IDE**.
3. **Pair your smartphone** with the **HC-05 Bluetooth module** (default password: `1234` or `0000`).
4. **Install a Bluetooth Controller app** (e.g., **Arduino Bluetooth Controller** from the Play Store).
5. **Send control commands** (`F` for forward, `B` for backward, `L` for left, `R` for right, `S` for stop).
6. **Enjoy wireless car control!**

## **Testing Instructions**
- Use a Bluetooth terminal app or a dedicated **Arduino Bluetooth Controller app**.
- Ensure the **Bluetooth module is paired** before testing.
- Verify that the **power connections** and **motor driver** are correctly wired.

## **Notes**
- Ensure the **Bluetooth module is working** and connected properly.
- The **HC-05 module operates at 3.3V logic**, use a **voltage divider** if required.
- Motors should have sufficient **power supply (e.g., 12V battery)** for optimal performance.
- You can modify **PWM signals** to adjust the **motor speed**.

## **Author**
- **Name:** Deepesh Munot
- **Email:** deepeshmunot71@gmail.com
- **GitHub:** [deepeshmunot04](https://github.com/deepeshmunot04)
- **LinkedIn:** [Deepesh Munot](https://www.linkedin.com/in/deepesh-munot-71b43b234)

