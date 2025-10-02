# OpenMRC  

A modern, open-source re-creation of the classic FireWire DTE recorders — powered by Raspberry Pi.  

![OpenMRC Banner](https://placehold.co/1000x200?text=OpenMRC+Project)  

---

## 🚀 Project Overview  

**OpenMRC** is a global community-driven project developing a **video/audio recorder** based on Raspberry Pi hardware.  
Our goal is to bring back the workflow of classic FireWire-based Digital Tape Equipment (DTE) recorders — but with a modern, open-source twist.  

Currently, around **8 contributors worldwide** are actively working on both hardware and software.  

---

## 🛠️ Hardware Projects  

### 🔹 Equip-1  
- FireWire board (VT6315N) for Raspberry Pi 4/5  
- Connects over PCIe ribbon cable  
- Prototype PCBs ordered  
- 3D-printable cases available  

### 🔹 FireBoard  
- Custom **Compute Module 5 (CM5)** carrier board  
- Built-in FireWire chip (VT6315N)  
- Features:  
  - Full-size HDMI  
  - DSI/CSI ports  
  - USB3 port  
  - MicroSD slot  
  - FireWire port  
- ~90% design complete, pending validation before PCB prototype order  
- 3D-printable cases in development  

---

## 💻 Software Development  

- **FFmpeg** chosen as the recording engine (replacing dvgrab)  
  - Active development  
  - Supports advanced features  
  - Allows realtime preview via `ffplay` on LCD or HDMI output  
- **Kernel optimizations** planned for efficiency and performance  
- GUI concepts:  
  - Hybrid **touchscreen + rotary encoder** interface (inspired by iPods & iPhones)  
- Development paths explored: **C programming, Qt for GUI, and experimental scripting**  
- Features in progress:  
  - Built-in level gauge  
  - Precompiled kernel for easy setup  
  - Potential dedicated distribution  

---

## 🎨 Design & Community  

- 3D-printed cases designed in parallel with hardware  
- Artists needed for an **official OpenMRC logo**  
- Active discussions and updates happening on Discord and Reddit  

---

## 🌍 Community & Updates  

Want realtime updates and to get involved?  
Join us here: [Computer Equipment Group Discord](https://discord.gg/XP8uHH9ArF)  

Follow updates on **r/tapeless** as well.  

---

## 📌 TL;DR  

- OpenMRC = **Open Source FireWire DV Recorder**  
- Hardware: Raspberry Pi + custom PCBs (Equip-1 & FireBoard)  
- Software: FFmpeg-based recording, optimized kernels, modern UI concepts  
- Global collaboration of engineers, designers, and developers  

---

## 📷 Gallery  

> Coming soon — hardware photos, PCB renders, and case designs.  

---

## 🙌 Contributing  

OpenMRC is a community project — contributions are welcome!  
Whether you’re into **hardware design, software development, case prototyping, or UI/UX design**, there’s a place for you.  

- Fork us on GitHub  
- Join the [Discord](https://discord.gg/XP8uHH9ArF)  
- Share ideas on r/tapeless  

---

## 📜 License  

OpenMRC is fully open source.  
License details will be announced soon (GPLv3 / CERN OHL under discussion).  

---

© 2025 OpenMRC Project. Community-powered.  
