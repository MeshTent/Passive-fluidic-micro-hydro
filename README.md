# Passive-fluidic-micro-hydro
A passive fluidic microhydro system for electricity generation 
# Passive Macro-Scale Fluidic Relaxation Oscillator for Micro-Hydro Power

An open-source, non-electronic fluidic logic system designed to harvest low-flow water sources to generate continuous micro-hydro power. This repository serves as a permanent public disclosure of "Prior Art" to keep this technology freely available for humanitarian use globally.

## 📜 License
This project is licensed under the **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** license. You are free to copy, modify, and distribute this design for non-commercial and humanitarian purposes. Commercial production requires explicit permission from the inventor.

---

## 💡 System Concept & Core Physics
This system functions as a macro-scale fluidic analog to an electronic **RCL relaxation oscillator**. It successfully converts a steady, low-velocity continuous fluid input (DC) into a sharp, periodic "stop-start" kinetic pulse output (AC) without the use of solid mechanical trip-switches or electronic control logic.

An engineer can understand the loop as an integrated fluidic circuit:
* **Input (Constant Voltage Source):** A **Triple Mariotte Array** that locks the effective pressure head, preventing pressure drop as the reservoir empties.
* **Timing Loop (RC Delay Network):** A **Capillary Wicking Matrix** (using a compact, porous container of stabilized compost or biochar) paired with a fluidic **Constriction Resistor**. The capillary suction acts as a capacitor, creating a phase lag as it saturates.
* **Switching Gate (Diode):** A **One-Way Check Valve** that remains closed until backpressure behind the constriction clears a distinct threshold, causing it to snap open.
* **Impulse Stroke (Inductive Kickback):** A **Dual Hydraulic Ram** layout. The sudden drop in local pressure when the valve acts triggers a rapid change in velocity. Because water is incompressible, this fluid inertia creates a massive kinetic energy spike (water hammer effect). This shockwave forces the wicking capacitor to drain/reset via a **porous drain**, starting the loop over again.

---

## 🛠️ Technical Specifications (10 L/s UK Prototype 2)
Optimized for ultra-low head constraints (such as strict UK temporary structural planning laws) to output a target **20 Watts** of electricity.


| Component | Specification / Dimension | Function |
| :--- | :--- | :--- |
| **Header Tank** | 1,000-Litre Standard IBC sized colapsible water butt Tote | Fluid buffer storage; provides a 100-second cycle window at maximum flow. |
| **Mariotte Air Intake** | 5 cm (2-inch) Sealed PVC Pipe | Maintains a steady vacuum seal and constant pressure head without internal sloshing. |
| **Downpipe** | 15 cm to 20 cm (6 to 8-inch) Pipe | Houses the falling water column; acts as the primary fluid inductor ($L$). |
| **Constriction** | 3.5 cm to 5 cm (1.5 to 2-inch) Reduction | Throttles flow to build up threshold pressure against the check valve. |
| **Wicking Capacitor** | 2 m² Surface Area Porous Tray | Sealed compost/biochar matrix to introduce the timing delay without needing high volume. |
| **Turbine Drop** | 50 cm Vertical Head | Directs pulsed output onto a gravity-driven overshot water wheel connected to a geared 12V DC motor. |

---

## 🌍 Humanitarian Scaling Potential (e.g., West Africa)
In rural, off-grid environments where height restrictions are absent, the system scales vertically to become highly energetic:
1. **Elevated Stacking:** 4 collapsible 1000l water butts  on an earth mound establishes a **2.5 to 3-metre head height**.
2. **Kinetic Multiplier:** Increasing the drop from 50 cm to 3 m increases kinetic energy output roughly **six-fold** ($v = \sqrt{2gh}$), enabling the use of high-efficiency, compact Pelton or Turgo micro-turbines.
3. **Passive Purification:** The natural hydrostatic pressure from a 3 m head is sufficient to push discharged water through ceramic filters,if they are used, in providing clean drinking water and village lighting simultaneously , otherwise it can be used for electricity and lighting .
