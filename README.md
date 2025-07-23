# 🚦 Traffic Signal System Simulator using C++ & OpenGL

A visually interactive **Traffic Light Controller** built using **C++** and **OpenGL**, simulating the real-world functioning of a smart traffic intersection using **Finite State Machines (FSM)**.

---

## 📌 Features

- 🟢 Graphical simulation of a 3-phase traffic light system  
- 🔁 FSM-based state transition logic  
- ⏱️ Real-time delay simulation for signal timing  
- 🎨 Built entirely in **C++ with OpenGL**, no microcontroller required  

---

## 🎯 Objectives

- Model a real-life traffic light system using software-based digital logic  
- Demonstrate Finite State Machine implementation in C++  
- Visualize state transitions and control logic with OpenGL  

---

## 🧠 FSM Logic

| State  | Action             | Duration (sec) |
|--------|--------------------|----------------|
| RED    | Stop vehicles       | 5              |
| GREEN  | Allow movement      | 5              |
| YELLOW | Prepare to stop     | 2              |

The system follows a simple cyclic pattern:  
**RED → GREEN → YELLOW → RED**

---

## 📁 Project Structure

```

📂 Traffic-Signal-System/
├── main.cpp          # Core logic & rendering
├── README.md         # Project description
└── Instructions.pdf  # Setup & run guide (optional)

````

---

## 🚀 Getting Started

### ✅ Requirements

- C++ Compiler (`g++`, Code::Blocks, or DevC++)
- OpenGL & GLUT libraries installed

### 💻 Compile & Run (Linux/macOS)

```bash
g++ main.cpp -o traffic -lGL -lGLU -lglut
./traffic
````

### 💻 Compile & Run (Windows - Code::Blocks/DevC++)

1. Install OpenGL or use preinstalled GLUT in DevC++
2. Open project in your IDE and run (`F9`)

---

## 🧩 Possible Extensions

* 🚶 Add pedestrian crossing with blinking signal
* 🚨 Emergency vehicle override logic
* ⏱️ Dynamic timing based on traffic density
* ⌨️ Keyboard input for manual signal control

---

## 👨‍💻 Author

**Aditya Dev**
*Electrical Engineering | Focused on Digital Logic, Embedded Systems, and C++*
[GitHub](https://github.com/yourusername) | [LinkedIn](https://linkedin.com/in/yourprofile)

---

## 📜 License

This project is licensed under the **MIT License**.
You are free to use, modify, and share this project for learning or demonstration purposes.

