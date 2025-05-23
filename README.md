# Steven Abdelshahid’s Portfolio

I’m a **Computer Engineering** student at UC Santa Cruz. I build embedded systems, FPGA designs, and low-level software.

---

## Projects

### Card-Dealing Robot  
Firmware + hardware for a servo-driven card dispenser with ultrasonic jam detection.  
**Tech:** C, PIC32, HC-SR04, PWM  
– Firmware architecture with multi-state control (feed/dispense/error/retry)  
– Adaptive HC-SR04 threshold logic to distinguish jams from normal feeds  
– 3D-printed mount calibration and sensor integration for precise alignment  
– Full test suite and API docs for future UI/telemetry integration  

### Dinorun FPGA Game  
Verilog implementation of the Chrome-dinosaur runner on an FPGA.  
**Tech:** Verilog, Quartus, VGA  
– Modular sprite/background rendering blocks  
– 640×480@60 Hz VGA timing logic  
– Testbenches for collision and state-machine validation  
– Git-based team workflow, synthesis-conflict resolution  

### BananaSlug Emulator  
Custom-ISA emulator from CSE 130, with memory, “GPU,” and syscall support.  
**Tech:** C, Linux syscalls, Autograder  
– CPU fetch-decode-execute pipeline and register file management  
– Virtual memory (code, heap, stack) with bounds checking  
– Memory-mapped framebuffer “GPU” for text/graphics output  
– Integrated read/write/open/close syscalls for I/O  
– Automated validation (50+ tests) via the CSE130 autograder  

### Sorting Visualizer Web App  
Interactive tool to animate Quick, Merge, and Bubble sorts.  
**Tech:** JavaScript, HTML, CSS  
– Shuffle, play/pause, and speed controls  
– Optimized 60 FPS rendering with `requestAnimationFrame`  
– Modular code for easy addition of new algorithms  
[View Project on GitHub](https://github.com/stevensamer03/sorting-visualizer)

### Toaster-Oven Controller  
Event-driven FSM for oven control with OLED readout.  
**Tech:** C, PIC32, SPI OLED  
– Hardware-abstraction layer + control logic separation  
– Non-blocking SPI driver to update OLED without IRQ clashes  
– PWM heater control and low-power modes  
– Oscilloscope/logic-analyzer testing  

### Roach Robot Test Harness  
Test framework for two-wheeled robot calibration and navigation.  
**Tech:** C, ES Framework, UART  
– Hierarchical state machines for calibration, navigation, obstacle avoidance  
– UART command/data streams for real-time sensor logging  
– Performance metrics logging to guide hardware tuning  

---

## Skills

- **Languages:** C, C++, Verilog, Python  
- **Embedded & Hardware:** PIC32, FPGA, SPI, I2C, UART, PWM, HC-SR04  
- **Tools:** Git, Linux, Eagle PCB, Fusion 360, Oscilloscope, Logic Analyzer  

---

> 📫 Feel free to reach out:  
> stevensamer2003@gmail.com • github.com/stevensamer03  
