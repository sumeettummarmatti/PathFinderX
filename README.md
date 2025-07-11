# 🏎️ PathFinderX – Smart Line Following Robot

PathFinderX is an advanced Arduino-powered robot that autonomously follows a black line, detects nearby obstacles, and responds to colors like red, green, and blue—just like an F1 car responding to pit signals. This project is a hands-on example of embedded systems, robotics, and sensor fusion for automation.

---

## 🚀 Features

- 🛣️ **Line Following** using dual IR sensors
- 🚧 **Obstacle Detection** with Ultrasonic Sensor (HC-SR04)
- 🎨 **Color Detection** (Red, Green, Blue) via TCS3200 Sensor
- 🧠 Simple yet smart decision logic for real-time path following

---

## 🧰 Components Used

| Component           | Description                        |
|---------------------|------------------------------------|
| Arduino Uno / Nano  | Microcontroller brain              |
| IR Sensors (2x)     | Line tracking (left & right)       |
| HC-SR04             | Ultrasonic distance sensor         |
| TCS3200             | Color sensor module                |
| L298N Motor Driver  | Controls DC motors                 |
| DC Motors + Wheels  | For movement                       |
| Chassis & Battery   | Robot frame and power              |
| Jumper Wires        | Connections                        |

---

## 🧠 How It Works

1. **IR Sensors** detect the black line on the surface.
2. **Ultrasonic Sensor** measures distance to obstacles and stops if anything is < 5 cm.
3. **TCS3200 Color Sensor** reads RGB input:
   - 🟥 Red – Stop
   - 🟦 Blue – Slow down
   - 🟩 Green – Speed up

---

## 🪛 Circuit

> 📸 *[[View the circuit diagram on Cirkit Designer IDE]](https://app.cirkitdesigner.com/project/80f72890-f2dc-473b-b27e-30c9b6459683)*

---

## ⚙️ Setup Instructions

1. **Assemble the hardware** according to the wiring diagram .
2. **Upload the code** from `/pathFinderX/code.ino` using Arduino IDE.
3. Place the robot on a **black line track** with optional colored zones.
4. Power on and watch it drive intelligently!

---

## 🧪 Demo

> 🎥 *[[Watch Demo on Vimeo]](https://vimeo.com/1095835070/0d1aff5f2e?ts=0&share=copy)*

---

## 💡 Use Cases

- Educational robotics kits
- Mini project for ECE/Robotics students
- Base for more advanced self-driving bots

---

## 📜 License

This project is open source under the [MIT License](./LICENSE).

---

## 🤝 Contributing

Pull requests are welcome. If you'd like to enhance features or add cool behaviours

---

## 📞 Contact

Have questions or feedback? Open an issue or reach out via GitHub discussions!

---

