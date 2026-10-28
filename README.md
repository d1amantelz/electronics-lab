# ⚡ Electronics Lab: Analog, Digital & Mixed-Signal Prototyping

> Hands-on experimental lab exploring discrete circuit design, timer ICs, logic gates, sensors, and PCB development from fundamental physics to physical hardware devices.

---

## 🛠️ Lab Infrastructure & Equipment
* **Soldering Station:** `FNIRSI HS-01` Smart Digital Iron (65W GaN PD powered) with CNC cartridge tips (`BC2`, `ILS`, `KU`, `KR`)
* **Consumables:** Eutectic `63/37` (0.8 mm, 2.0% Rosin-Core) solder, `RMA-223` flux gel, brass tip cleaner
* **Workstation:** `S-160` Heat-resistant anti-static silicone mat, cast-iron third-hand tool
* **Test & Measurement:** Digital Multimeter, 9V DC power sources, solderless breadboards

---

## 🔬 Hardware Projects Gallery

| # | Project | Architecture / Highlights | Working Photos |
|---|---|---|:---:|
| `01` | [**Adjustable Strobe**](./01-adjustable-strobe-555) | NE555 astable multivibrator, negative feedback loop, frequency tuning via 500 kΩ potentiometer | [View](./01-adjustable-strobe-555#--working-hardware-photos) |
| `02` | [**Dual Pomodoro Timer**](./02-pomodoro-timer-555) | Push-pull totem-pole output on Pin 3 (Current Sinking vs Sourcing), anti-phase Dual-LEDs, 1000 µF macro-timing | [View](./02-pomodoro-timer-555#--working-hardware-photos) |
| `03` | [**Optical Theremin**](./03-optical-theremin-555) | Contactless audio frequency synth, GL5528 photoresistor modulation, DC-blocking AC speaker coupling | [View](./03-optical-theremin-555#--working-hardware-photos) |

---

## 📚 Core Electrical Principles Mastered
1. **RC Time Constants:** $t = 0.693 \cdot R \cdot C$, charge and discharge curves, frequency calculations.
2. **Totem-Pole Output Stages:** Dual-switch push-pull drivers capable of sourcing and sinking up to 200 mA.
3. **Impedance Matching & Protection:** Pull-up/pull-down resistor logic to eliminate floating antenna pins; series current limiters.
4. **Capacitive Coupling (`AC Coupling`):** Blocking DC bias while conducting dynamic audio waveforms to prevent voice coil burn-in.
5. **Sensor Integration:** Interfacing analog photo-conductive cells (LDR) into oscillating timing loops.

---

## 👤 Author
* **GitHub:** [@d1amantelz](https://github.com/d1amantelz)
* **Roadmap:** Discrete Analog $\longrightarrow$ Logic ICs (74HC/4000) $\longrightarrow$ Microcontrollers (STM32/ESP32) $\longrightarrow$ Custom KiCad PCBs.
