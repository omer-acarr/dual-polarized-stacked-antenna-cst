# Dual-Polarized Stacked-Up Patch Antenna Design
## Electromagnetic Simulation & Analysis (CST Studio Suite)


## 📡 Project Overview
This project involves the design and high-fidelity simulation of a **Dual-Polarized Stacked-Up Patch Antenna**. The design is optimized for broadband performance and high isolation between ports, suitable for modern RF communication systems.

### 🛠 Technical Specifications
* **Software:** CST Studio Suite 2025
* **Structure:** Stacked-up patch with dual-feed mechanism
* **Substrates:** * Rogers RT-duroid 5880 (Loss Free)
    * FR-4 (Lossy)
* **Mesh Resolution:** 874,380 Mesh Cells (High Precision)

---

## 📊 Key Results

### 1. S-Parameter Performance
The simulation demonstrates excellent port isolation and wideband impedance matching.

| Parameter | Performance | Notes |
| :--- | :--- | :--- |
| **Resonance Band** | 1.7 GHz - 2.6 GHz | Wideband coverage |
| **Isolation ($S_{12}$)** | -30 dB to -40 dB | High decoupling between H/V ports |
| **Return Loss** | < -10 dB | Optimized at 1.8 GHz & 2.5 GHz |

### 2. Radiation Characteristics (@ 2.0 GHz)
* **Directivity (Dir.):** `8.960 dBi`
* **Total Efficiency:** `-2.803 dB`
* **Radiation Efficiency:** `-0.4132 dB`

---

## ⚙️ Design Parameters
```cpp
// Geometric variables used in the parametric model
double h1 = 1.58;   // Substrate 1 Thickness
double h2 = 38.0;   // Ground/Patch Dimension
double h3 = 0.508;  // Layer separation
double h4 = 0.508;  // Layer separation
double h5 = 9.0;    // Feed height
