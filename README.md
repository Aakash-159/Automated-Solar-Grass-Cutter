# Automated-Solar-Grass-Cutter
An Arduino-based solar-powered grass cutting robot with automatic sun tracking system
# 🌱 Automated Solar Grass Cutter with Sun Tracking System

This project is an intelligent and eco-friendly grass cutting robot that runs on solar energy and uses a sun-tracking system to maximize power generation. Built using Arduino, this system helps in automatic grass trimming with minimal human effort and ensures optimal battery charging through solar tracking.

---

## ⚙️ Features

- 🪫 Solar-powered with rechargeable battery
- ☀️ Sun tracking using LDR sensors for maximum solar efficiency
- 🤖 Automated grass cutter powered by DC motor
- 🧭 Obstacle avoidance using ultrasonic sensors (optional)
- ♻️ Environment-friendly and cost-efficient

---

## 🛠️ Components Used

| Component                  | Quantity |
|---------------------------|----------|
| Arduino UNO               | 1        |
| Solar Panel (6V or 12V)   | 1        |
| LDR Sensors               | 4        |
| DC Motors                 | 2–4      |
| Motor Driver (L293D)      | 1        |
| Servo Motor (for panel)   | 1        |
| Wheels                    | 4        |
| Blades (for cutting)      | 1        |
| Ultrasonic Sensor (HC-SR04) | 1–2    |
| Battery (6V/12V 4.5Ah)    | 1        |
| Chassis, Breadboard, Wires, etc. | – |

---

## 💻 Arduino Code

The Arduino code is located in the `Code/` folder.

- `sun_tracking.ino` – Controls servo motor for solar tracking
- `grass_cutting.ino` – Controls motor for grass cutting
- `main.ino` – Integrates all systems together

---

## 🧪 Working Principle

1. Solar panel charges the battery while tracking sunlight using LDRs and servo motor.
2. The robot moves autonomously across the grass field.
3. A DC motor blade mounted at the front trims grass while moving.
4. Optionally, an ultrasonic sensor detects and avoids obstacles.


---

## 📬 Contact

**Author:** Aakash V  
**Email:** aakashaakash95893@gmail.com  
**GitHub:** Aakash-159(https://github.com/Aakash-159)

