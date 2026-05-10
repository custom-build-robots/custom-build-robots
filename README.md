# Hi, I'm Ingmar 👋

**Automotive AI engineer.** I work on local AI inference, agentic systems, and embedded robotics. Currently focused on running open-weight LLMs and VLMs close to the workload - on edge-class hardware and multi-GPU lab workstations @home.

Based in Munich, Germany 🇩🇪



<img src="https://ai-box.eu/wp-content/uploads/2024/06/Real_Time_Landmine_Detection-1024x768.jpg" alt="Jetson Nano FPM-1 mine detector YOLO" width="70%" />

---

## 🦞 Coming next: ESP-Claw robot car - physical AI

The red lobster has landed on my workbench 🦞

Next experiment: equip one of the school-project cars with an **ESP32-P4-M3-DEV** board and get **[ESP-Claw](https://github.com/espressif/esp-claw)** running on it. ESP-Claw is Espressif's open-source agent framework for IoT. The idea: inside the robot car runs the full loop of sensing, reasoning, and execution directly on the chip, with native MCP support (as both client and server) and Lua scripts loaded at runtime. Inspired by OpenClaw, but built for microcontrollers.

What I want to find out: what happens when a robot car can be *talked to* instead of flashed? When behavior is changed at runtime through chat or voice? When the agentic loop runs inside the car itself, and an 8-year-old can tell the car what to do and the car answers back in the physical world?

I don't know yet whether it will work end-to-end on the ESP32-P4. The board is in the mail. That's exactly why I'm doing it.

<img src="https://ai-box.eu/wp-content/uploads/2026/05/Roboter_Auto_ESP32_Schulprojekt_11_public-scaled.jpg" alt="ESP-Claw lobster mascot on the ESP32 robot car" width="600" />

---

## 🏫 Current: robotics in primary schools - Talente-Tour 2026

In May 2026 I'm running a robotics project week for 3rd and 4th graders as part of the **Talente-Tour 2026**. Children build small ESP32-based robot cars from scratch - wiring up sensors, programming motor drivers, and getting them to drive. The goal: hands-on robotics from the very start, with every component understandable and repairable. No black boxes, no plug-and-play kits.

<img src="https://custom-build-robots.com/wp-content/uploads/2026/05/Roboter_Auto_ESP32_Schulprojekt_10_public-scaled.jpg" alt="Talente-Tour 2026 ESP32 robot cars" width="600" />

---

## 📚 Books & Publications

- ***Roboter-Autos mit dem ESP32*** — Rheinwerk Verlag. Hands-on guide to building autonomous robot cars with the ESP32 microcontroller, sensors, and motor drivers.
- ***Robot Cars with the Raspberry Pi*** — Building self-driving robot cars on the Raspberry Pi platform.
- ***Souveräne KI in Europa*** — *forthcoming, publication planned for August 2026*, Rheinwerk Verlag. Covers sovereign AI infrastructure, local inference stacks, and agentic systems running outside the major cloud platforms.
- **Co-author**, *"Inside the GenAI Transformation: A Paradox Theory Perspective on Intra-Organizational Tensions"* — in preparation for HICSS 2027.

<p>
  <img src="https://s3-eu-west-1.amazonaws.com/cover2.galileo-press.de/print/9783367111442_267.png" alt="Roboter-Autos mit dem ESP32" height="220" />
  <img src="https://s3-eu-west-1.amazonaws.com/cover2.galileo-press.de/print/9783836267557_267.png" alt="Robot Cars with the Raspberry Pi" height="220" />
</p>
<img src="https://custom-build-robots.com/wp-content/uploads/2025/10/ESP32_Roboter_Auto_Gabelstapler_Erweiterung_small.jpg" alt="ESP32 robot car with forklift extension" width="100%" />
---

## 🛠️ What I'm working on

- **Local AI inference at scale** - operating Ollama, vLLM, and llama.cpp with Qwen3, Nemotron-family, Gemma, and other open-weight models. Personal lab on dual NVIDIA RTX A6000 / A6000 Ada workstations; Ubuntu-based servers.
- **Agentic systems** - Hermes Agent and OpenClaw-based frameworks with MCP-style tool calling, custom local-primary/local-fallback provider routing, edge-friendly models in the 2–7B class for low-latency inference next to the production line.
- **Computer vision for safety-critical applications** - through the Demine Foundation, building a thermal/IR + RGB data-fusion pipeline (real captured imagery + 3D-rendered synthetic data) with YOLO for detection of organically shaped anti-personnel mines.

<img src="https://ai-box.eu/wp-content/uploads/2026/05/NVIDIA_RTX_A6000_ADA-scaled.jpg" alt="Local AI inference lab — NVIDIA RTX A6000 Ada" width="600" />

---

## 🚀 Featured projects

A few repos that show what I do best:

- **[Voxtral-Real-time-Speech-to-Text-vLLM](https://github.com/custom-build-robots/Voxtral-Real-time-Speech-to-Text-vLLM)** - Real-time speech transcription with Mistral *Voxtral-Mini-4B-Realtime* running on NVIDIA GPUs via vLLM
- **[SongBloom-AI-Assistant-with-OLLAMA](https://github.com/custom-build-robots/SongBloom-AI-Assistant-with-OLLAMA)** - Local AI assistant for full-length song generation, built on Ollama with structured prompt engineering
- **[ai-agents-with-CrewAI](https://github.com/custom-build-robots/ai-agents-with-CrewAI)** ⭐74 - Multi-agent web-research workflow using CrewAI
- **[Installation-Scripts-for-Generative-AI-Tools](https://github.com/custom-build-robots/Installation-Scripts-for-Generative-AI-Tools)** - Setup scripts for GenAI tooling on Ubuntu
- **[esp32-roboter-auto](https://github.com/custom-build-robots/esp32-roboter-auto)** - Autonomous ESP32 robot car (HC-SR04 obstacle detection, MPU6050, PS5 controller via Bluepad32)
- **[6-Axis-Desktop-Robotic-Arm-Raspberry-Pi](https://github.com/custom-build-robots/6-Axis-Desktop-Robotic-Arm-Raspberry-Pi)** ⭐52 - Web-controlled 6-axis desktop robotic arm

---

## 🔧 Areas

`Local LLM/VLM inference` · `Agentic AI (Hermes Agent, OpenClaw, ESP-Claw, CrewAI)` · `MCP tool calling` · `Physical AI` · `NVIDIA GPU infrastructure` · `vLLM · Ollama · llama.cpp` · `Embedded robotics (ESP32, Raspberry Pi)` · `Computer vision (YOLO, SAM)` · `Self-driving (Donkey Car, Udacity SDC ND)` · `Industrial AI deployment`

---

## 🌐 Find me elsewhere

- 🧠 **[ai-box.eu](https://ai-box.eu)** - primary site for AI/inference content
- 🤖 **[custom-build-robots.com](https://custom-build-robots.com)** - robotics & maker blog
- 💼 **[LinkedIn](https://linkedin.com/in/ingmar-stapel)**
- 📬 [mail@stapel-ingmar.de](mailto:mail@stapel-ingmar.de)
