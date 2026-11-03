<div align="center">

# Hi, I'm Antonio Galdes 👋

### Computer Engineer · MSc Artificial Intelligence · Malta

*Software that touches the physical world: GPUs, microcontrollers, sensors, and now robots.*

</div>

---

## 👨‍💻 About me

I am a Computer Engineering graduate (First Class Honours, Dean's List) from the University of Malta, and I have just finished my **MSc in Artificial Intelligence**. The dissertation is written and submitted, and only the viva stands between me and the title.

I like the point where code meets hardware: making something fast on a GPU, getting a sensor to tell the truth on an ESP32, or teaching an agent to cope when its position estimate is wrong.

## 🤖 Right now

- **Learning robotics.** Perception, state estimation, planning and control, working through ROS 2 and simulation.
- Wrapping up the MSc with the **viva**.

## ⚡ Previously: performance engineering

Before moving towards robotics, a good part of my time went on making things run quickly: CUDA kernels for volumetric medical data, SIMD vectorised image resampling, and multi-threaded numerical code in C++. Those projects are below.

---

## 🚀 Projects

### 🧠 Dissertation: uncertainty-aware reinforcement learning for autonomous parking
**[Uncertainty-Conditioned RL with Evidential Policy Networks](https://github.com/Expo39/Uncertainty-Conditioned-RL-with-Evidential-Policy-Networks-for-Autonomous-Systems)**

A parking policy is only as good as its position estimate, and that estimate degrades when GNSS does. I fed the EKF covariance into a PPO agent and gave it an evidential output head, so the agent knows both how unsure the localisation is and how unsure it is of its own action. Trained in CARLA with ROS 2.
`Python` `PyTorch` `ROS 2` `CARLA`

### ⚡ CUDA 3D Discrete Wavelet Transform
**[CUDA-3D-DWT](https://github.com/Expo39/CUDA-3D-DWT)**

A multi-level 3D wavelet transform on the GPU, built for large medical volumes and validated on the CHAOS dataset.
`CUDA` `C++`

### 🖼️ SIMD image resampling
**[SIMD-Image-Processor](https://github.com/Expo39/SIMD-Image-Processor)** · **[Threaded-Monte-Carlo](https://github.com/Expo39/Threaded-Monte-Carlo)**

Two studies in squeezing the CPU: Lanczos resampling with SIMD intrinsics, and Monte Carlo integration spread across threads.
`C++`

### 🌡️ Home ambient monitoring
**[Home-Ambient-Monitoring-System](https://github.com/Expo39/Home-Ambient-Monitoring-System)**

An ESP32 that watches temperature, humidity and CO2, listens for a fire alarm with an FFT, and answers by opening a window and running a fan. A web dashboard shows it all live.
`ESP32` `C++`

### 🔊 Embedded signal processing
**[DTMF_Decoder](https://github.com/Expo39/DTMF_Decoder)** · **[LEGv8](https://github.com/Expo39/LEGv8)**

A touch-tone decoder using the Goertzel algorithm on a microcontroller, and a single-cycle LEGv8 processor simulator that traces every instruction.
`C` `C++`

### 🍳 My Cookbook
**[My_Cookbook](https://github.com/Expo39/My_Cookbook)** · [live site](https://expo39.github.io/My_Cookbook/)

A recipe site for family and friends, with serving scaling, unit conversion, a cook mode and an AI sous-chef. One Rust core runs at build time and in the browser through WebAssembly, so the two can never disagree about an amount.
`Rust` `WebAssembly`

### 🥋 Code Dojo
**[Code-Dojo](https://github.com/Expo39/Code-Dojo)**

A training system for getting good at programming without handing the work to an AI: spaced repetition, timed drills and Claude Code as a tutor that questions and reviews but never writes the answer.
`Python`

### 📊 Group project: Malta traffic accidents
**[ICS5110 Applied ML](https://github.com/Expo39/ICS5110-AppliedML_Project)**

Police press releases and news articles turned into a modelling dataset with LLM-assisted extraction, then four classifiers compared. I built the gradient boosting model.
`Python` `Optuna`

---

## 🛠️ Toolbox

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=flat-square&logo=django&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=flat-square&logo=ros&logoColor=white)

![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
