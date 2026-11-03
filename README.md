# Antonio Galdes

Computer Engineer based in Malta, working on **GPU computing (CUDA), embedded systems and edge AI**, with a focus on making signal, image and learning pipelines fast and reliable on constrained hardware.

First Class Honours graduate in Computer Engineering (Dean's List), University of Malta. MSc Artificial Intelligence dissertation, September 2026.

---

## Current focus

- **Uncertainty-aware reinforcement learning** for autonomous systems: propagating EKF localisation uncertainty through evidential policy networks (PyTorch, ROS 2, CARLA).
- **Performance engineering**: CUDA kernels, SIMD vectorisation and multi-threading.
- **Developer tooling**: learning environments and small full-stack applications.

---

## Selected projects

### AI and machine learning

| Project | Description | Stack |
|---|---|---|
| [Uncertainty-Conditioned RL](https://github.com/Expo39/Uncertainty-Conditioned-RL-with-Evidential-Policy-Networks-for-Autonomous-Systems) | MSc dissertation. Autonomous parking under degraded GNSS, with EKF covariance fed to a PPO agent and an evidential Normal-Inverse-Gamma output head. | Python, PyTorch, ROS 2, CARLA |
| [ICS5110 Applied ML](https://github.com/Expo39/ICS5110-AppliedML_Project) | Group project modelling Malta traffic accidents from police press releases and news articles, with LLM-assisted extraction and four compared classifiers (my part: gradient boosting). | Python, Jupyter, Optuna |

### High-performance computing

| Project | Description | Stack |
|---|---|---|
| [CUDA-3D-DWT](https://github.com/Expo39/CUDA-3D-DWT) | Multi-level 3D Discrete Wavelet Transform on the GPU, validated on the CHAOS medical imaging dataset. | CUDA, C++ |
| [SIMD-Image-Processor](https://github.com/Expo39/SIMD-Image-Processor) | Image resampling with Lanczos filtering and SIMD vectorisation. | C++ |
| [Threaded-Monte-Carlo](https://github.com/Expo39/Threaded-Monte-Carlo) | Multi-threaded Monte Carlo integration. | C++ |

### Embedded systems and IoT

| Project | Description | Stack |
|---|---|---|
| [Home-Ambient-Monitoring-System](https://github.com/Expo39/Home-Ambient-Monitoring-System) | ESP32 sensing (temperature, humidity, CO2), FFT-based fire detection from audio, automated servo and fan response, and a React and Node.js dashboard. | ESP32, TypeScript, React, Node.js |
| [DTMF_Decoder](https://github.com/Expo39/DTMF_Decoder) | Real-time touch-tone decoder using the Goertzel algorithm, with LCD output. | Embedded C |
| [LEGv8](https://github.com/Expo39/LEGv8) | Single-cycle datapath simulator for the LEGv8 architecture, with detailed execution tracing. | C++ |

### Software and tooling

| Project | Description | Stack |
|---|---|---|
| [My_Cookbook](https://github.com/Expo39/My_Cookbook) ([live site](https://expo39.github.io/My_Cookbook/)) | Static recipe site with serving-size scaling, unit conversion, cook mode and an optional AI assistant. The same Rust core runs at build time and in the browser through WebAssembly. | Rust, WebAssembly, SvelteKit |
| [Code-Dojo](https://github.com/Expo39/Code-Dojo) | Personal training system for deliberate practice, with spaced repetition and an AI tutor that explains and reviews but never writes the code. | Python |
| [Inventory-Management-System](https://github.com/Expo39/Inventory-Management-System) | The same system implemented in C++ and Java, communicating through gRPC and Protocol Buffers. | C++, Java, gRPC |

---

## Tools

**Languages:** C++ · C · CUDA · Python · Rust · TypeScript · JavaScript · Java
**ML and vision:** PyTorch · OpenCV · scikit-learn · Optuna
**Systems:** Linux · Docker · Git · ESP32 · ROS 2
