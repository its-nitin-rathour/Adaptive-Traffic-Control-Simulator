# AutoSignalX 🚦 – Intelligent Traffic Signal Simulator

AutoSignalX is a real-time, multi-lane traffic signal simulator that models a 4-way intersection using Python and Pygame. Designed for educational and research purposes, it demonstrates concepts like multithreading, dynamic signal timing, vehicle behavior simulation, and object-oriented programming in a distributed control environment.

---

## 🎯 Features

- 🧠 **Adaptive Signal Logic** based on real-time vehicle density and type (car, bus, bike, etc.)
- 🛣️ **4-Way Intersection Simulation** using accurate lane logic and turning behavior
- 🌀 **Multithreaded Engine** for signal switching, vehicle generation, and simulation timing
- 🧱 **Modular OOP Design** for extensibility and clean architecture
- 🎨 **Pygame Visualization** with signal lights, vehicle icons, timers, and counts

---

## 🛠 Tech Stack

| Component       | Technology          |
|----------------|---------------------|
| Language        | Python 3.x          |
| GUI             | Pygame              |
| Concepts Used   | OOP, Multithreading, Simulation, Real-Time Systems |
| Optional Future | YOLO for Vehicle Detection (planned) |

---

## 🚀 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/AutoSignalX.git
cd AutoSignalX
```

### 2. Install Dependencies

```bash
pip install pygame
```

### 3. Run the Simulation

```bash
python simulation.py
```

---

## 📁 Folder Structure

```
AutoSignalX/
├── images/
│   ├── mod_int.png               # Background (intersection)
│   ├── signals/                  # Red, yellow, green signal images
│   └── [direction]/[vehicle].png # Vehicle images (car, bus, truck...)
├── simulation.py                 # Main simulation logic
└── README.md                     # Project documentation
```

> ⚠️ Ensure that all image assets are placed correctly inside the `/images/` folder. If any image is missing or incorrectly named, the simulator will crash.

---

## 🎥 Demo

> Add a GIF or screen recording of the simulation here

---

## 💡 Key Learning Outcomes

* Real-time decision-making in smart traffic systems  
* Use of Python OOP for modeling complex entities (signals, vehicles, behaviors)  
* Multithreading in simulations to run concurrent systems (timers, movement)  
* Visual simulation with Pygame for interactive learning

---

## 📌 Future Enhancements (Optional)

* Integrate YOLO-based real-time vehicle detection (currently commented)  
* Add GUI controls for signal override or manual mode  
* Simulate pedestrian signals and emergency vehicle prioritization

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

## 👩‍💻 Author

**Mansi Gupta**  
*M.Tech – Software Engineering @ Delhi Technological University*  
GitHub: [Mansi2202](https://github.com/Mansi2202)  
Project: [AutoSignalX](https://github.com/Mansi2202/AutoSignalX)

---
