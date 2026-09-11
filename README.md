# Distributed Vehicle Vibration Data Acquisition System

A low-cost, multi-point MEMS sensor system for analyzing/exploring and monitoring vibration behaviour in passenger vehicles.

**Core Research Question:** *Can low-cost MEMS accelerometers provide actionable vibration telemetry across distributed measurement points on a vehicle?*

This is a personal learning project focused on developing practical skills in embedded systems, electronics and data analysis by building a sensor network from scratch.

The project currently focuses on the sensor network and hardware design. 
The system is being developed in KiCad, with C/C++ firmware and Python-based data analysis planned for later stages.


Development Status & Roadmap

## Project Status & Roadmap

## Tech Stack

* **EDA / Hardware:** KiCad 8
* **Processing:** ESP32-C3 Mini (RISC-V)
* **Sensing:** ADXL345 (3-axis MEMS, SPI + INT1 data-ready line)
* **Bus / Physical Layer:** RS-485 transceiver (UART), daisy-chain topology with switchable 120 Ω termination
* **Firmware (Planned):** C / C++
* **Analytics (Planned):** Python (NumPy, SciPy for FFT and spectral analysis)

---
### Completed (Current Stage)
- [x] Distributed system architecture and multi-drop(daisy-chain) bus concept
- [x] Sensor node schematic capture in KiCad (SPI, UART-RS485, power decoupling)
- [x] Electrical Rules Check (ERC) verified

---
### Next Steps 
- [ ] Central Data Acquisition Unit (CDU) PCB design and prototyping
- [ ] Sensor node firmware development (C/C++, SPI DMA/FIFO, RS-485 packet protocol)
- [ ] Multi-point road testing on passenger vehicle
- [ ] Python vibration analysis pipeline (FFT, time/frequency domain feature extraction)
- [ ] Potential ML / TinyML integration for vibration anomaly detection (feasibility study)

